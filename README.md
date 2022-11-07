# Lab Exercise 001
1. Write a program called CheckPassFail which prints "PASS" if the int variable "mark" is more than or equal to 50; or prints "FAIL" otherwise. The program shall always print “DONE” before exiting.
	Hint:
		Use >= for greater than or equal to comparison.
		/**
		 * Trying if-else statement.
		 */
		public class CheckPassFail {  // Save as "CheckPassFail.java"
			public static void main(String[] args) {  // Program entry point
				int mark = 49;   // Set the value of "mark" here!
				System.out.println("The mark is " + mark);

				// if-else statement
				if ( ...... ) {
					System.out.println( ...... );
				} else {
					System.out.println( ...... );
				}
				System.out.println( ...... );
			}
		}
		Try mark = 0, 49, 50, 51, 100 and verify your results.
2. Write a program called CheckOddEven which prints "Odd Number" if the int variable “number” is odd, or “Even Number” otherwise. The program shall always print “bye!” before exiting.
		Hint
			n is an even number if (n % 2) is 0; otherwise, it is an odd number. Use == for comparison, e.g., (n % 2) == 0.



			/**
			 * Trying if-else statement and modulus (%) operator.
			 */
			public class CheckOddEven {   // Save as "CheckOddEven.java"
				public static void main(String[] args) {  // Program entry point
					int number = 49;       // Set the value of "number" here!
					System.out.println("The number is " + number);
					if ( ...... ) {
						System.out.println( ...... );   // even number
					} else {
						System.out.println( ...... );   // odd number
					}
					System.out.println( ...... );
				}
			}
			Try number = 0, 1, 88, 99, -1, -2 and verify your results.
3. Write a program called PrintNumberInWord which prints "ONE", "TWO",... , "NINE", "OTHER" if the int variable "number" is 1, 2,... , 9, or other, respectively. Use (a) a "nested-if" statement; (b) a "switch-case-default" statement.
	Hint
		/**
		 * Trying nested-if and switch-case statements.
		 */
		public class PrintNumberInWord {   // Save as "PrintNumberInWord.java"
			public static void main(String[] args) {
				int number = 5;  // Set the value of "number" here!

				// Using nested-if
				if (number == 1) {   // Use == for comparison
					System.out.println( ...... );
				} else if ( ...... ) {
					......
				} else if ( ...... ) {
					.....
				} else {
					......
				}
				// Using switch-case-default
				switch(number) {
					case 1: 
						System.out.println( ...... ); break;  // Don't forget the "break" after each case!
					case 2: 
						System.out.println( ...... ); break;
						 .....
					default: System.out.println( ...... ); 
				}
			}
		}
4. Write a program called PrintDayInWord which prints “Sunday”, “Monday”, ... “Saturday” if the int variable "dayNumber" is 0, 1, ..., 6, respectively.  Otherwise, it shall print "Not a valid day". Use (a) a "nested-if" statement; (b) a "switch-case-default" statement.
Try dayNumber = 0, 1, 2, 3, 4, 5, 6, 7 and verify your results.


