# CountWordsInALine
import java.util.Scanner;

public class CountAWordInAString {

	public static void main(String[] args) {

		Scanner get = new Scanner(System.in);
		System.out.println("Enter String");
		String input = get.nextLine();
		String[] words = input.split(" ");
		int count = words.length;
		System.out.println("Number of words in the String : " + count);
	}

}
