## Nate Paynes Programming 1 Portfolio!

# Projects from the 2017-2018 year

### Space Game

  Our Group Project of the year, a simple game involving avoidance of an enemy ship and its lasers.
  
  <img width="993" alt="spaceship game" src="https://user-images.githubusercontent.com/26355832/38640418-71fee262-3d91-11e8-979f-ec8e61fca1e3.png">
  
  [SpaceShip Game](https://github.com/godofdeathftw/Spaceship-Shooter)
  
### PigLatin

  Basic Java code to translate English Text into PigLatin
  
  ![PigLatin App](https://github.com/Wheaties0/PigLatin/raw/master/PigLatin.png)
  
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
  
  ![Box](https://github.com/Wheaties0/ShapeTester/raw/master/Box.png)
  
  ![Sphere](https://github.com/Wheaties0/ShapeTester/raw/master/Sphere.png)
  
  ![Pyramid](https://github.com/Wheaties0/ShapeTester/raw/master/Pyramid.png)
  
  [Source Code](https://github.com/Wheaties0/ShapeTester/tree/master/src)

### Calculator
	
A Java application, presenting a simple operational calculator

![Calculator App](https://github.com/Wheaties0/Calculator/raw/master/Calculator.png)

[Source Code](https://github.com/Wheaties0/Calculator/tree/master/src)
  
### Numbers
  
  A java application with an integrated random number generator. The user inputs values to guess the random value
  
  ```
import java.util.*;
public class Numbers {
	public static void main(String[] args) {
		int user = 0;
		int counter = 0;
		Scanner scanner = new Scanner(System.in);
		//Random Class
		int random = (int )(Math.random()*101);
		//Println
		System.out.println("Welcome to the Guessing Game! Guess a Number between 1 and 100:");

			while (user != random){
				user = scanner.nextInt();
				counter ++;
				if(user < random) {
					System.out.println("Number is too low:");

			} else if (user > random) {
				System.out.println("Number is too High:");
			} else {
				System.out.println("Great! You guessed correctly in "+ counter +" times");
			}

		}

	}

}
  ```
  
  
### Screensaver

A Copy of the classic Windows XP screensaver in 2 dimensions, developed in Java

![Calculator App](https://github.com/Wheaties0/ScreenSaver/raw/master/ScreenSaver.png)

[Source Code](https://github.com/Wheaties0/ScreenSaver/tree/master/src)


