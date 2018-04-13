## Nate Paynes Programming 1 Portfolio!

# Projects from the 2017-2018 year

### Space Game

  Our Group Project of the year, a simple game involving avoidance of an enemy ship and its lasers.
  
### PigLatin

  Basic Java code to translate English Text into PigLatin
  
  ![PigLatin App](https://github.com/Wheaties0/PigLatin/blob/master/PigLatin.png)
  
  ```
import java.util.Scanner;

public class PigLatin {
	public static void main(String[] args) {
		Scanner keyboard = new Scanner (System.in);
		String Str1, Str2;
		System.out.print("Enter a Word to translate to Pig Latin: ");
		Str1 = keyboard.nextLine();
		Str2 = Str1.substring(0,1);
		char first = Str1.charAt(0);
		if (first == 'a' || first == 'e' || first == 'i' || first == 'o' || first == 'u') {
			System.out.println("Your new word is: " + Str1.substring(0) + "ay");
		}else {
			System.out.println("Your new word is: " + Str1.substring(1) + Str2 + "ay");
		}

	}
}
  ```
  
### Shape Tester

  A Basic Java app by entering certain parameters, can give the values of Volume and Surface Area of a specified Shape
  
  ```
  import java.util.*;

public class ShapeTester {
	public static void main (String [] args) {
		
		//Box Method
		Box box = new Box();
		box.Volume();
		box.SurfaceArea();

		//Sphere Method
		Sphere sphere = new Sphere();
		sphere.Volume();
		sphere.SurfaceArea();
		
		//Pyramid Method
		Pyramid pyramid = new Pyramid();
		pyramid.Volume();
		// pyramid.SurfaceArea();
	}
}
```
  Box Class
  ```
  import java.util.Scanner;

public class Box {
	float Height;
	float Breadth;
	float Length;

	 public void Volume() {
	 	System.out.println("Volume Calculator for Box");
		Scanner keyboard = new Scanner(System.in);
		System.out.println("Enter Length Value");
		float Length = keyboard.nextFloat();
		System.out.println("Enter Height Value");
		float Height = keyboard.nextFloat();
		System.out.println("Enter Breadth Value");
		float Breadth = keyboard.nextFloat();

		float Volume = Length * Height * Breadth;

		System.out.println("The Volume of your Box is " + Volume);
	}

	public void SurfaceArea() {
		System.out.println("Surface Area Calculator for Box");
		Scanner keyboard = new Scanner(System.in);
		System.out.println("Enter Length Value");
		float Length = keyboard.nextFloat();
		System.out.println("Enter Height Value");
		float Height = keyboard.nextFloat();
		System.out.println("Enter Breadth Value");
		float Breadth = keyboard.nextFloat();

		float SurfaceArea = (2 * Length * Breadth) + (2 * Length * Height) + (2 * Height * Breadth);

		System.out.println("The Surface Area of your Box is " + SurfaceArea);
	}
}
  ```
  Sphere Class
  ```
  import java.util.Scanner;
import java.lang.Math.*;

public class Sphere {
	double Radius;

	 public void Volume() {
	 	System.out.println("Volume Calculator for Sphere");
		Scanner keyboard = new Scanner(System.in);
		System.out.println("Enter Radius Value");
		double Radius = keyboard.nextDouble();

		double Volume = (4 * Math.PI * Radius * Radius * Radius) / 3;

		System.out.println("The Volume of your Sphere is " + Volume);
	}

	public void SurfaceArea() {
		System.out.println("Surface Area Calculator for Sphere");
		Scanner keyboard = new Scanner(System.in);
		System.out.println("Enter Radius Value");
		double Radius = keyboard.nextDouble();

		double SurfaceArea = 4 * Math.PI * Radius * Radius;

		System.out.println("The Surface Area of your Sphere is " + SurfaceArea);
	}
}
  ```
  Pyramid Class
  ```
  import java.util.Scanner;
import java.lang.Math.*;
import static java.lang.Math.sqrt;

public class Pyramid {
	float Height;
	float Breadth;
	float Length;

	 public void Volume() {
	 	System.out.println("Volume Calculator for Pyramid");
		Scanner keyboard = new Scanner(System.in);
		System.out.println("Enter Length Value");
		float Length = keyboard.nextFloat();
		System.out.println("Enter Height Value");
		float Height = keyboard.nextFloat();
		System.out.println("Enter Breadth Value");
		float Breadth = keyboard.nextFloat();

		float Volume = (Length * Height * Breadth) / 3;

		System.out.println("The Volume of your Pyramid is " + Volume);
	}
}
  ```
  
### Calculator
  
### Numbers
  
### Screensaver
