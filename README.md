# Internshala-CoreJava-all-module-assignments

ASSIGNMENT-1

Hey! Now that you’re familiar with basics of Java programming, let’s write a small java program to generate a Student ID Card.
Desired Output:
——————————————
Name: Sriyank Siddhartha
Age: 25
Blood Group: A+
——————————————
Your group is RED
——————————————
Problem Statement: Write a Java program that will take user input and print his Name, Age, Blood Group and also his Group to which he belongs to in the school.

package com.company;
import java.util.Scanner;

public class Main {
    public static void main (String[] args)  {
        String name;
        int Age;
        char bloodGroup;
        Scanner scanner=new Scanner(System.in);
        System.out.println("Enter your name:  ");
        name=scanner.nextLine();
        System.out.println("Enter your Age:  ");
        Age=scanner.nextInt();
        System.out.println("Enter your bloodGroup:  ");
        bloodGroup =scanner.next().charAt(0);


        System.out.println("Name  " + name);
        System.out.println("Age  " + Age);
        System.out.println("Bloodgroup  " + bloodGroup);


        String Student;
        if (Age>=20)  {
            Student = "Red";
        }
        else if (Age>=15)  {
            Student = "bule";
        }
        else {
            Student = "Yellow";
        }
        System.out.println("Your Group is  " + Student);
    }
}
