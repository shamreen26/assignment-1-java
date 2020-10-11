# assignment-1-java

import java.util.*;
import java.io.*;

public class employee
{
	String name;
	int age;
	String city;
	public static void main (String[] args) 
	{
		employee emp1 = new employee();
                emp1.name="Farzana";
                emp1.age=20;
                emp1.city=" Chennai";
		employee emp2 = new employee();
                emp2.name="Muheed";
                emp2.age=15;
                emp2.city="Bangalore";
		System.out.println("The name is:"+emp1.name);
		System.out.println("The age is:"+emp1.age);
		System.out.println("The city is:"+emp1.city);
		System.out.println("The name is:"+emp2.name);
		System.out.println("The age is:"+emp2.age);
		System.out.println("The city is:"+emp2.city);
		
	}
	}

}

Output:

 The name is Farzana
 The age is 20
 The city is Chennai
 The name is Muheed
 The age is 15
 The city is Banglore
 
 

