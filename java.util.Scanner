import java.util.Scanner;

public class CircleCalculator {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        
        // Request input from the user
        System.out.print("Enter the radius of the circle: ");
        
        // Check if the user entered a valid number
        if (input.hasNextDouble()) {
            double radius = input.nextDouble();
            
            // Validate the radius input (should be positive)
            if (radius > 0) {
                double area = Math.PI * Math.pow(radius, 2);
                double circumference = 2 * Math.PI * radius;
                
                // Display the results
                System.out.printf("Radius: %.2f%n", radius);
                System.out.printf("Area: %.2f%n", area);
                System.out.printf("Circumference: %.2f%n", circumference);
            } else {
                System.out.println("Error: The radius must be a positive number.");
            }
        } else {
            System.out.println("Error: Invalid input. Please enter a valid number.");
        }

        input.close();
    }
}
