# October 4th Afternoon Exercise

## Task Description

Write an application that takes all the information about a specific user :
name , age , gender , education , email , profession , company
Then out put a CV.

## Angela's Work

'
package main.java;

import java.util.Scanner;

public class ExerciseOct4 {

    public static void main(String[] args) {

        Scanner myinput = new Scanner(System.in);
        System.out.println("We will generate a paragraph about you: ");
        System.out.println("Enter your name : ");
        String name = myInput.nextLine();

        System.out.println("Enter your age : ");
        int age = myInput.nextInt();

        System.out.println("Enter your gender : ");
        String gender = myInput.nextLine();

        System.out.println("Enter your education : ");
        String education = myInput.nextLine();

        System.out.println("Enter your email : ");
        String email = myInput.nextLine();

        System.out.println("Enter your profession: ");
        String profession = myInput.nextLine();

        System.out.println("Enter your company : ");
        String company = myInput.nextLine();


        //finally combine everything
        System.out.println(cvDescription(name, age, gender, education, email, profession, company));

    }

 
public static String cvDescription(String name, int age, String gender, String education, String email,
String profession, String company){
return "Dear Reader, my name is " + name +
". I am " + age +
"years old and a "+ gender +
". I have reached the " + education +
"level of education. You can reach me at my email address: " + email +
". Currently, I work as a " + profession +" at " + company +
". Thank you and have a nice day!";

}

}