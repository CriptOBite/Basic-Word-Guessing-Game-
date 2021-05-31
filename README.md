# Basic-Word-Guessing-Game-
This is a basic and simple to use template for a word guessing game. (This is also being used as a school project) 
Just copy this code into your IDE of choice (make sure you have the jdk from oracle installed)
Change some of the settings and your done Just click the green triangle to run this.
Only copy what is after the equal symbols 
==================================================================

 //Basic Interactive Java Game Made By CriptOBite



import java.util.Scanner;

public class Main {
   public static void main(String[] args) {
       String GameName = "Input your games name";
       System.out.println ("Welcome to " + GameName);
       System.out.println ("Type what you think the code is");
       Scanner UserInput = new Scanner (System.in);
       String StoreInput = UserInput.nextLine ();
       String CorrectAnswer = "set this to the correct answer that you want";
       if(StoreInput.equals (CorrectAnswer)){
           System.out.println ("YOU WIN");


       } else System.out.println ("YOU LOST");
)
   }
}
=========================================================



