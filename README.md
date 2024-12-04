Printing Incrementing Inverted Triangle Pattern:
In this JAVA program we’re going to code basic right triangle number pattern pattern program .

Take a input from user as enter the row and coloum and then store it in variable called row and col and take count=col+2 After this take loop start from i=row to i– and then take inner loop start from j=1 to j++ and then print statement  to print count and then write count– after that take line changement statement

Java Program for Basic Right Triangle Number Pattern (Inverted)
Algorithm:
Take a input from user that is row and col and store it in count=col+2
Take two loops one for each line (say ‘i’) and other for each digit in a particular line (say ‘j’). i starts from i=row  to  i–and j starts from 1 j=1 to j++
inside j loop print count variable
Outside the inner j loop print count–
At the end of main for loop print System.out.println();
Code in Java:
import java.util.Scanner;
public class Pattern1 {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		System.out.println("Enter row and col");
		int row = sc.nextInt();
		int col = sc.nextInt();
		int count = col+2;
		
		for (int i = row; i >= 1; i--) {
			for (int j = 1; j<=i ; j++) 
				System.out.print(count);
			count--;
			System.out.println();
		}
	}

}
