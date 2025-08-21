package Tamilarasi;
import java.util.Scanner;
public class VotingEligibility {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        // Step 1: Input age
        System.out.print("Enter your age: ");
        int age = sc.nextInt();

        // Step 2: Check eligibility
        if (age >= 18) {
            System.out.println("You are eligible to vote.");
        } else {
            System.out.println("You are not eligible to vote. Please wait " + (18 - age) + " more years.");
        }

        sc.close();
    }
}# Find-to-eligible-for-vote
voting eligibility based on age if the age isa les than 18 print remining yrs to vote
