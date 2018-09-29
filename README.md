# SoulTest

import java.util.Scanner;
public class Graph
{
   public static void main(String[] args) 
     {
       int a =5;
       int b =9;
       double root1, root2, d;
       Scanner s = new Scanner(System.in);
       System.out.println("Given quadratic equation:ax^2 + bx = 15");
       System.out.print("Value of a is"+a);
       System.out.print("Value of b is"+b);
       System.out.println("Given quadratic equation:"+a+"x^2 + "+b+"x + ");
       d = b * b - 4 * a * c;
       if(d > 0)
       {
           System.out.println("Roots are real and unequal");
           root1 = ( - b + Math.sqrt(d))/(2*a);
           root2 = (-b - Math.sqrt(d))/(2*a);
           System.out.println("First root is:"+root1);
           System.out.println("Second root is:"+root2);
       }
       else if(d == 0)
       {
           System.out.println("Roots are real and equal");
           root1 = (-b+Math.sqrt(d))/(2*a);
           System.out.println("Root:"+root1);
       }
       else
       {
           System.out.println("Roots are imaginary");
       }
   }
}
