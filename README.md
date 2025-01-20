# Collect-and-store-student-details
Collect and Store Student Details

import java.util.Scanner;

public class StudentDetails {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter student name: ");
        String name = sc.nextLine();
        System.out.print("Enter student age: ");
        int age = sc.nextInt();
        System.out.print("Enter student grade: ");
        double grade = sc.nextDouble();

        System.out.println("Student Details:");
        System.out.println("Name: " + name);
        System.out.println("Age: " + age);
        System.out.println("Grade: " + grade);
    }
}

Output

Enter student name: John  
Enter student age: 18  
Enter student grade: 95.5  

Student Details:  
Name: John  
Age: 18  
Grade: 95.5
