# assignment-1-java
import java.util.*;
import java.io.*;
public class employee
{ 
public void em1()
{
String name="Farzana";
int age=20;
String city=" Chennai";
System.out.println("The name is:"+name);
System.out.println("The age is:"+age);
System.out.println("The city is:"+city);
}
                
public void em2()
{
String name="Muheed";
int age=15;
String  city="Bangalore";
System.out.println("The name is:"+name);
System.out.println("The age is:"+age);
System.out.println("The city is:"+city);
}

public static void main (String[] args) 
{
employee emp1 = new employee();
employee emp2 = new employee();
		
emp1.em1();
emp2.em2();
 }
}

Output:

The name is:Farzana
The age is:20
The city is: Chennai
The name is:Muheed
The age is:15
The city is:Bangalore
 
 

