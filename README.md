# LowertoUpper
Takes a letter's case in a string and converts it from to lower to upper or vice versa
import java.util.*;
import java.lang.*;
import java.io.*; 
public class LowertoUpper {

	public static void main(String[] args) {
		int i, len;
		char ch; 
		Scanner x = new Scanner(System.in);
		System.out.println("Enter string: ");
		String words = x.nextLine();
		len = words.length();
		for (i=0; i<len; i++) {
			ch = words.charAt(i);
			if (Character.isUpperCase(ch))
				System.out.print(Character.toLowerCase(ch));
			else
				System.out.print(Character.toUpperCase(ch));
		}
		
	}

}
