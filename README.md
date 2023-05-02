Download Link: https://assignmentchef.com/product/solved-cmsc203-assignment-2-random-number-guesser
<br>
Build an application that will receive a guess and report if your guess is the random number that was generated.  Your application will narrow down the choices according to your previous guesses, and continue to prompt you to enter until you guess correctly.

Notice that if you divide the choices in half each iteration, you will need at most log<sub>2</sub>(100) ~ 7 guesses.

You will use the utility class RNG.java.

<table width="100%">

 <tbody>

  <tr>

   <td><strong>Concepts tested by this assignment</strong></td>

  </tr>

 </tbody>

</table>




<ul>

 <li>A driver and a utility class</li>

 <li>UML class diagrams or pseudo-code</li>

 <li>Java fundamentals, including decision structures, loops</li>

 <li>Selection control statements</li>

 <li>Repetition control statements</li>

 <li>Input validation loops (in RNG.java)</li>

 <li>Relational and logical operators</li>

 <li>Random number generation (in RNG.java)</li>

</ul>




<table width="100%">

 <tbody>

  <tr>

   <td><strong>Classes</strong></td>

  </tr>

 </tbody>

</table>







<strong>Data Element Class </strong><strong>– RNG </strong>

<ul>

 <li>Provided</li>

 <li>This file will generate a random number between 1 and 100</li>

 <li>Note that the method “rand” is a static method, so the java file does not need to be instantiated to use it. Call rand with the following: RNG.rand(100) to generate a random number between 0 and 99.</li>

 <li>Study this class. You will want to use four methods from this class: rand, resetCount, getCount and inputValidation.</li>

</ul>

<strong> </strong>

<strong>Driver Class </strong><strong>– RandomNumberGuesser</strong>

<ul>

 <li>Student created</li>

 <li>This is the driver class for RNG that contains a main method.</li>

 <li>The driver is responsible to:

  <ul>

   <li>print a header</li>

   <li>ask the user for an initial guess of the Random Number between 0 and 100.</li>

   <li>Print out the result for that guess using the methods from the RNG class.</li>

   <li>Allow user to give another guess between the previous low and high guesses.</li>

   <li>Display the number of guesses</li>

   <li>When user guesses correctly, ask if the user wants to try another round.</li>

   <li>Print the Programmer’s name at the end</li>

   <li>Refer to the program sample run for more clarification.</li>

   <li>For testing, you may print out the randomly-generated number.</li>

   <li>In comments, list the author’s name (yours)</li>

  </ul></li>

 <li>Data Validation. The following data is validated by the RNG method inputValidation:

  <ul>

   <li>Guesses must be an integer between the previous low guess and high guess.</li>

  </ul></li>

 <li>

  <ul>

   <li>There should be an attribute named randNum</li>

   <li>There should be attributes named nextGuess, highGuess, and lowGuess</li>

  </ul></li>

 <li>Add any necessary methods to modularize your code.</li>

</ul>










<table width="100%">

 <tbody>

  <tr>

   <td><strong>Assignment Details</strong></td>

  </tr>

 </tbody>

</table>










Your program should respond similar to the following sample runs:

== Example Run 1 (one iteration) ===========

== Example Run 2 (one iteration, one guess over the limit) ===========

== Example Run 3 (two iterations) ===========

Take screenshots of two runs of your program. Your runs should include feedback on previous low and high guesses, at least one example of a guess not within the previous low and high guesses, and an example of a second try with a new random number.  You may use <u>either</u> an IDE or command-line processing. Store your files in the repo you created in GitHub in Lab 1, and take a screenshot of the GitHub repo.





