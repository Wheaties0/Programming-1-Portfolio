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
  
  [Source Code](https://github.com/Wheaties0/ShapeTester/tree/master/src)
  ---
  ![Box](https://github.com/Wheaties0/ShapeTester/blob/master/Box.png)
  ---
  ![Sphere](https://github.com/Wheaties0/ShapeTester/blob/master/Sphere.png)
  ---
  ![Pyramid](https://github.com/Wheaties0/ShapeTester/blob/master/Pyramid.png)

### Calculator
  
### Numbers
  
### Screensaver
