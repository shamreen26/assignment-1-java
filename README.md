# assignment-1-jaimport java.util.*;
import java.io.*;

public class employee
{
	String name="Farzana";
	int age=20;
	String city="Chennai";
	public static void main (String[] args) 
	{
		employee emp1 = new employee();
		employee emp2 = new employee();
		System.out.println("The name is:"+emp1.name);
		System.out.println("The age is:"+emp1.age);
		System.out.println("The city is:"+emp1.city);
		System.out.println(emp2.name);
		System.out.println(emp2.age);
		System.out.println(emp2.city);
	}

}
