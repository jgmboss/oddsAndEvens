# oddsAndEvens
import java.util.Scanner;
public class oddsAndEven
{
     public static void main (String args []){
        Scanner input = new Scanner (System.in);
        System.out.println ("Please enter a number");
        int number = input.nextInt();
        System.out.println ( "The numbr is...");
        if (number % 2 == 0){
            System.out.println ("Even!");
        }
        else{
            System.out.println ("Odd!");
        }
    }
}
