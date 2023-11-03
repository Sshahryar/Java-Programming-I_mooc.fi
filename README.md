# JavaProgrammingI_mooc.fi

Repository where I will be uploading my submissions for exercise solutions from the "Java Programming I" course from the University of Helsinki.

The exercise solutions were submitted using the TMC (test my code) plugin from the Univerity of Helsinki using IntelliJ Idea, the submissions stored here are for keepsake, personal achievement and public access to my course completion.  

The exercise submissions are placed in a folder based on the part of the course they were from.

For example, the exercise solution submissions for part 1 will be in the "Part1ExerciseSubmissions" folder, below will be the parts of the courses with their exercises and solution submissions all in order.

Details about the readings, quizzes and other components of the course will be in the wiki.
 
## The Exercises

### Part1ExerciseSumbissions

#### 1. Sandbox.java

#### Submission:

    public class Sandbox {

    public static void main(String[] args) {
        // Write your program here
        }
    }

#### Purpose:

The purpose of this program was to simply submit something through the TMC (Test My Code) plugin from the University of Helsinki, to get familiarized with it. 

#### Output:

Nothing. Simply a submission exercise.

#### 2. AdaLovelace.java

#### Submission:

    public class AdaLovelace {

    public static void main(String[] args) {
        // Write your program here
        System.out.println("Ada Lovelace");
        }
    }

#### Purpose:

Simple console based output. 

#### Output:

![image](https://github.com/Sshahryar/Java-Programming-I_mooc.fi/assets/123003299/d064e77f-1b5a-4fd0-92fb-ea84ab0cc527)

#### 3. OnceUponaTime.java

#### Submission:

    public class OnceUponATime {

    public static void main(String[] args) {
        // Write your program here
        System.out.println("Once upon a time");
        System.out.println("there was ");
        System.out.println("a program");
        }
    }

#### Purpose:

Printing more than one line.

#### Output:

![image](https://github.com/Sshahryar/Java-Programming-I_mooc.fi/assets/123003299/efdde23b-1be4-4e8c-bac6-6501f53b85cc)

#### 4. Dinosaur.java

#### Submission:

    public class Dinosaur {

    public static void main(String[] args) {
        // Write your program here
        System.out.println("Once upon a time");
        System.out.println("there was");
        System.out.println("a dinosaur");
        }
    }

#### Purpose:

Using the 'sout' command to quickly write printing lines. 

##### Output: 

![image](https://github.com/Sshahryar/Java-Programming-I_mooc.fi/assets/123003299/02884462-b9c0-4b62-8674-66aa7d3517c4)

#### 5. Message.java

#### Submission:

    import java.util.Scanner;

    public class Message {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.println("Write a message:");
        String message = scanner.nextLine();

        System.out.println(message); 
        }
    }

#### Purpose: 

Getting a string from the user.

#### Output:

![image](https://github.com/Sshahryar/Java-Programming-I_mooc.fi/assets/123003299/621e7847-124a-41b6-b5c3-f3675c3e7504)

#### 6. HiAdaLovelace.java

#### Submission: 

    public class HiAdaLovelace {

    public static void main(String[] args) {
        String name = "Ada Lovelace!";
        System.out.println("Hi " + name);
        }
    }

#### Purpose:

Using strings with a text output.

#### Output:

![image](https://github.com/Sshahryar/Java-Programming-I_mooc.fi/assets/123003299/d5d0113e-c6bb-4b12-a728-258f51a4bc5f)

#### 7. MessageThreeTimes.java

#### Submission:

    import java.util.Scanner;

    public class MessageThreeTimes {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.println("Write a message:");
        String message = scanner.nextLine();

        System.out.println(message);
        System.out.println(message);
        System.out.println(message);
        }
    }

#### Purpose:

Printing a user inputed string three times in a row.

#### Output:

![image](https://github.com/Sshahryar/Java-Programming-I_mooc.fi/assets/123003299/60ff15be-0f07-4737-b349-97c70238f7e4)

#### 8. Greeting.java

#### Submission:

    import java.util.Scanner;

    public class Greeting {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.println("What's your name?");
        String message = scanner.nextLine();

        System.out.println("Hi " + message);
        }
    }

#### Purpose:

Greeting a user after they input their name using strings.

#### Output:

![image](https://github.com/Sshahryar/Java-Programming-I_mooc.fi/assets/123003299/61763a21-0113-495a-9cf3-80563ab1e9d7)

#### 9. Coversation.java

#### Sumbission:

    import java.util.Scanner;

    public class Conversation {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.println("Greetings! How are you doing?");
        String doing = scanner.nextLine();

        System.out.println("Oh, how interesting. Tell me more!");
        String more = scanner.nextLine();

        System.out.println("Thanks for sharing!");

         }
    }

#### Purpose:

Using user string inputs to form a little conversation.

#### Output:

![image](https://github.com/Sshahryar/Java-Programming-I_mooc.fi/assets/123003299/9c1ef37e-fd6b-4b8d-9211-61e4abf3ef19)
