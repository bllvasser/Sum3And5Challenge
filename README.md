# Sum3And5Challenge
package academy.learnprogrmming;

public class Main {

    public static void main(String[] args) {

        int count = 0;
        int sum = 0;
        for (int number = 1; number < 1000; number++) {
            if ((number % 3 == 0) && (number % 5 == 0)) {
                count++;
                sum += number;
                System.out.println("Found number = " + number);

            }
            if (count == 5) {
                break;
            }
        }
        System.out.println("Sum = " + sum);

    }
}
"C:\Program Files\Java\jdk-15.0.1\bin\java.exe" "-javaagent:C:\Users\nadiy\OneDrive\Desktop\IntelliJ IDEA Community Edition 2020.2.3\lib\idea_rt.jar=50141:C:\Users\nadiy\OneDrive\Desktop\IntelliJ IDEA Community Edition 2020.2.3\bin" -Dfile.encoding=UTF-8 -classpath C:\Users\nadiy\IdeaProjects\ForLoopExercises\out\production\ForLoopExercises academy.learnprogrmming.Main
Found number = 15
Found number = 30
Found number = 45
Found number = 60
Found number = 75
Sum = 225

Process finished with exit code 0
