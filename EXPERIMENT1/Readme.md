# EXPERIMENT1
## TITLE:1a.)primitive datatype
```
class DefaultValues {
byte b; short s; int i; long 1; float f; double d;
Char c;
boolean bool;
public static void main(String[] args) {
DefaultValues obj = new DefaultValues ();
System.out.println("Default value of byte
: " + obj.b);
System.out.println("Default value of short : " +obj.s);
System.out.println("Default value of int
: " + obj.i);
System.out.println("Default value of long : " + obj.l);
System.out.println("Default value of float : " + obj.f);
System.out.println("Default value of double : " + obj.d);
System.out.println("Default value of char
: ''+ obj.ct"''');
System.out.println( "Default value of boolean: " + obj.bool);  }
}
```
# output
<img width="182" height="88" alt="1a output" src="https://github.com/user-attachments/assets/c9a73948-65a8-4146-b2b9-cdcdc6c1f726" />


# EXPERIMENT1b
## TITLE:1b.)quadratic equation
```
import java.util.Scanner;
class QuadraticRoots {
public static void main (String[l args) {
double a, b, c, d; double rootl, root2;
Scanner sc = new Scanner (System.in);
System.out.print("Enter a, b and c values: ");
a = sc.nextDouble();}{
b = sc. nextDouble();
c = sc.nextDouble ();
d = b*b -4*a* c;
System.out.println ("Discriminant (D) = " + d);
if (d > 0){
oot1 = (-b + Math.sqrt(d)) .
00€2 = (-D - Math.sart (d)) / (2 * a)
System.out.println("Roots are real and distinct");
System.out.println("Root1 = " + I00t1);
System.out.printin ("Root2 = " + root2) ;
else if (d == 0) {
root1 = -b / (2 * a);
System.out.println("Roots are real and equal");
System.out.println("Root = " + I0ot1);}
else {
System.out.println("Roots are imaginary");
File:
1b. java
sc.close();
}
```
# ouput
![1b output](https://github.com/user-attachments/assets/023c4405-6490-4e8c-8934-fb7582f9c098)

