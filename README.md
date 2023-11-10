# cloud-3 C. Check if input is a pangram or not:
import java.util.Scanner;

public class PangramCheck {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Enter a sentence: ");
        String sentence = scanner.nextLine().toLowerCase();
        boolean isPangram = isPangram(sentence);
        System.out.println("Is Pangram? " + isPangram);
    }

    public static boolean isPangram(String sentence) {
        // Your logic to check if the sentence is a pangram
        // ...

        return isPangram; // Return true if it is a pangram, false otherwise
    }
}
