# softwareLab213

practice programs



// Online Java Compiler

// Use this editor to write, compile and run your Java code online

import java.util.Scanner;

public class Main {

&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner sc = new Scanner(System.in);

&nbsp;       System.out.println("Enter the coefficent of 'a':  ");

&nbsp;       double a = sc.nextDouble();

&nbsp;       System.out.println("Enter the coefficent of 'b':  ");

&nbsp;       double b = sc.nextDouble();

&nbsp;       System.out.println("Enter the coefficent of 'c':  ");

&nbsp;       double c = sc.nextDouble();

&nbsp;       

&nbsp;       double d = b\*b - 4\*a\*c;

&nbsp;       if (d > 0){

&nbsp;           double e = (-b + Math.sqrt(d))/(2\*a);

&nbsp;           double f = (-b - Math.sqrt(d))/(2\*a);

&nbsp;           System.out.println("roots are real and distint");

&nbsp;           System.out.println("e =" +e);

&nbsp;           System.out.println("f ="+f);





&nbsp;       }

&nbsp;       else if(d == 0){

&nbsp;           double root = -b/2\*a;

&nbsp;           System.out.println("root"+root);

&nbsp;           System.out.println("root are equal");

&nbsp;           

&nbsp;       }

&nbsp;       else {

&nbsp;           double rp = -b/2\*a;

&nbsp;           double img = Math.sqrt(-d)/(2\*a);

&nbsp;           System.out.println("roots are complex and distint");

&nbsp;           System.out.println("e ="+rp+"+"+img+"i");

&nbsp;           System.out.println("f ="+rp+"+"+img+"i");



&nbsp;       }

&nbsp;       



&nbsp;       

&nbsp;   }

}
/////comments
