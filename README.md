# Unit_1.3_Assignment
//transform user decimal into a binary equivalent string

import java.util.Scanner;

class Main {
  public static void main(String[] args) {
    Scanner userFloat = new Scanner(System.in);
    System.out.println("Enter a decimal number: ");

    String userBinary = userFloat.nextFloat();
    System.out.println("The binary equivalent of " + userFloat + " is: " + userBinary);  // Output user input
  }
}

