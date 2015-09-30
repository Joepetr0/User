# UserRole
import java.util.Scanner;
public class UserRole
{
   public static void main(String[] args)
   { 
      System.out.println("What Role are you?\n" + "Administrator, Faculty, Staff, Student or Guest.");
      Scanner keyboard = new Scanner(System.in);
      String userRole = keyboard.next();
      switch(userRole)
      {
         case "Administrator":
         System.out.println("Welcome " + userRole + "!");
         break;
         case "Faculty":
         System.out.println("Welcome " + userRole + "!");
         break;
         case "Staff":
         System.out.println("Welcome " + userRole + "!");
         break;
         case "Student":
         System.out.println("Welcome " + userRole + "!");
         break;
         case "Guest":
         System.out.println("Welcome " + userRole + "!");
         break;
         default:
         System.out.println("Invalid Role.");
         break;
      }
   }
}
