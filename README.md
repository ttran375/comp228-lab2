# LAB \#2 – Java Methods

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/ttran375/comp228-lab2)

[![Style Check](https://github.com/ttran375/comp228-lab2/actions/workflows/main.yml/badge.svg)](https://github.com/ttran375/comp228-lab2/actions/workflows/main.yml)

## Exercise 1

Write a Java application that simulates a test. The test contains **at
least five** questions about first three lectures of this course. Each
question should be a multiple-choice question with 4 options.

Design a **Test** class. Use programmer-defined methods to implement
your solution. For example:

- create a method to simulate the questions – *simulateQuestion*

- create a method to check the answer – *checkAnswer*

- create a method to display a random message for the user –
  *generateMessage*

- create a method to interact with the user - *inputAnswer*

Display the questions using methods of ***JOptionPane*** class. Use a
loop to show all the questions.

For each question:

- If the user finds the right answer, display a random congratulatory
  message (“Excellent!”,”Good!”,”Keep up the good work!”, or “Nice
  work!”).

- If the user responds incorrectly, display an appropriate message and
  the correct answer (“No. Please try again”, “Wrong. Try once more”,
  “Don't give up!”, “No. Keep trying..”).

- Use random-number generation to choose a number from 1 to 4 that will
  be used to select an appropriate response to each answer.

- Use a switch statement to issue the responses, as in the following
  code:

``` java
switch ( randomObject.nextInt( 4 ) )
{
    case 0:
    return( "Very good!" );
    // ……
}

```

At the end of the test display the number of correct and incorrect
answers, and the percentage of the correct answers.

Your main class will simply create a Test object and start the test by
calling **inputAnswer** method.

(5 marks)

## Exercise 2

Design a Lotto class with one array instance variable to hold three
random integer values (from 1 to 9). Include a constructor that randomly
populates the array for a lotto object. Also, include a method in the
class to return the array.

Use this class to simulate a simple lotto game in which the user chooses
a number between 3 and 27. *The user runs the lotto up to 5 times and
each time the sum of lotto numbers is calculated*. *If the number chosen
by the user matches the sum*, the user wins and the game ends. *If the
number does not match the sum within five rolls*, the computer wins.

Use methods of JOptionPane class to interact with the user.

(3 marks)

## Exercise 3

Write a Java class that implements a set of three overloaded static
methods. The methods should have different set of parameters and perform
similar functionalities. Call the methods within main method and display
the results.

(2 marks)
