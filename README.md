// Online Java Compiler
// Use this editor to write, compile and run your Java code online
import java.util.Scanner;
 class HelloWorld {
     public static void main(String[]args){
         System.out.println("Enter a number from 1-7:");
         Scanner scanner = new Scanner(System.in);
         int n = scanner.nextInt();
         if (n == 7){
           System.out.println("Sunday");  
         }
         else if (n==1){
         System.out.println("Monday");  
          
         }
         else if (n==2){
           System.out.println("Tuesday");  
         }
         else if (n == 3){
           System.out.println("Wednesday");  
         }
        else if (n == 4){
           System.out.println("Thursday");  
         }
         else if (n == 5){
           System.out.println("Friday");  
         }
         else if (n == 6){
           System.out.println("Saturday");  
         }
         else{
             System.out.println("Not available");
         }
     }
 }
