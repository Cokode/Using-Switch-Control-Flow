# Using-Switch-Control-Flow
An exercise from a course I am studying. 


public class SwitchStatement {

    public static void main(String[] args) {

        char grade = 'I';
        switch(grade) {
            case 'A':
                System.out.println("He scored grade A");
                break;
            case 'B':
                System.out.println("He scored grade B");
                break;
            case 'C':
                System.out.println("He scored grade C");
                break;
            case 'D':
                System.out.println("He scored grade D");
                break;
            case 'E': case 'F' : case 'G': case 'H' : case 'I':
                System.out.println("He scored one of the following grades E, F, G, H, I ");
                System.out.println("actual grade scored is: " + grade);
                break;
            default:
                System.out.println("None meet the match");
                break;

        }
    }
}
