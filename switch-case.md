# program
Welcome to Aditya Septa Project

Java program that uses switch - case

public class Program {
    public static void main(String[] args) {

	// Loop through 0, 1, and 2.
	for (int i = 0; i <= 2; i++) {
	    // Switch on number.
	    switch (i) {
		case 1: {
		    System.out.println("One: " + i);
		    break;
		}
		case 2:
		case 3: {
		    System.out.println("Two or three: " + i);
		}
		default: {
		    System.out.println("Default case: " + i);
		}
	    }
	}
    }
}

Output

Default case: 0
One: 1
Two or three: 2
Default case: 2
