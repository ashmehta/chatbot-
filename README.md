# chatbot-

/**
 * Write a description of class CounselorChatbot here.
 * 
 * @author (your name) 
 * @version (a version number or a date)
 */
import java.util.Scanner;
import java.util.List; 
import java.util.Arrays;
public class CounselorChatbot
{
    // instance variables - replace the example below with your own
    private int x;

    /**
     * Constructor for objects of class CounselorChatbot
     */
    public CounselorChatbot()
    {
        // initialise instance variables
        x = 0;
        List<String> messages = Arrays.asList("English 3", "Pre-Calculus", "AP Chemistry", "AP US History", "AP Computer Science", "AP Mandarin" );
    }

    /**
     * An example of a method - replace this comment with your own
     * 
     * @param  y   a sample parameter for a method
     * @return     the sum of x and y 
     */
    public void main()
    {
        Scanner user_input = new Scanner( System.in );
        System.out.println("Hello, How can I help you?");
        System.out.println("For help with classes, type in \"classes\"");
        System.out.println("For help with a transcript, type in \"transcript\"");
        System.out.println("For help with dropping classes, type in \"dropping class\"");
        System.out.println("For help with grades, type in \"grades\"");
        String utility = user_input.next();
        if (utility.equals("classes")){
            Classhelp();
        }
        else if (utility.equals("transcript")){
            Transcripthelp();
        }
        else if (utility.equals("dropping classes")) {
            Droppinghelp();
        }
        else if (utility.equals("grades")) {
            Gradehelp(); 
        }
        
        
    }
    public void Classhelp()
    {
        System.out.print("hello"); 

    }
    public void Transcripthelp()
    {
        System.out.print("hello there"); 

    }
    public void Droppinghelp()
    {
        System.out.print("hello there child"); 

    }
    public void Gradehelp()
    {
        System.out.print("hello there children"); 

    }
}
