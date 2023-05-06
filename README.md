Download Link: https://assignmentchef.com/product/solved-ecs30-assignment-2
<br>
<h1>Problem 1: charproperties.c</h1>

Write a program that reads in a char and prints the following properties (in order) of the char, if they apply:

<ul>

 <li>The char is an uppercase letter.</li>

 <li>The char is a lowercase letter.</li>

 <li>The char is a vowel.</li>

 <li>The char is a digit.</li>

 <li>The char is punctuation.</li>

 <li>The char is a tab.</li>

 <li>The char is a double quote.</li>

</ul>

This documentation for ctype.h will be useful: <a href="https://www.tutorialspoint.com/c_standard_library/ctype_h.htm">https://www.tutorialspoint.com/c_ </a><a href="https://www.tutorialspoint.com/c_standard_library/ctype_h.htm">standard_library/ctype_h.htm</a><a href="https://www.tutorialspoint.com/c_standard_library/ctype_h.htm">.</a> Example output:

[<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="f18382968882949db18192c0c6">[email protected]</a> <sup>˜</sup>]$ ./charproperties

Please enter a character: a

The char is a lowercase letter.

The char is a vowel.

[<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="d1a3a2b6a8a2b4bd91a1b2e0e6">[email protected]</a> <sup>˜</sup>]$ ./charproperties

Please enter a character: ” The char is punctuation.

The char is a double quote.

[<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="7d0f0e1a040e18113d0d1e4c4a">[email protected]</a> <sup>˜</sup>]$ ./charproperties

Please enter a character: 8 The char is a digit.

<h1>Problem 2: roshambo.c</h1>

Implement rock paper scissors. The user will input ’r’ for rock, ’p’ for paper, ’s’ for scissors. On any other entry your program should report an error. Your program must randomly generate its own rock, paper, or scissors, and compare it with the input to determine the winner.

Example output:

Rock, paper, or scissors? r I rolled rock. We tie!

Rock, paper, or scissors? s I rolled paper. You win!

Rock, paper, or scissors? p

I rolled scissors. You lose!

Rock, paper, or scissors? a

Error: you did not enter ’r’, ’p’, or ’s’!

<h1>Problem 3: unitconversion.c</h1>

In this problem your program will convert units of volume for liquid measurements. One gallon is four quarts, one quart is two pints, one pint is two cups, and one cup is eight ounces. The user will first input a current measurement and unit of volume as a positive integer and one of g for gallons, q for quarts, p for pints, c for cups, or o for ounces separated by a space. Then the user will input a desired unit of volume as one of g for gallons, q for quarts, p for pints, c for cups, or o for ounces. If the user’s input does not match this specification, print the relevant errors in the examples below and quit.

Example output:

Enter your current measurement and unit of volume: 16 o

Enter your desired unit of volume: c You have 2 cups of liquid.

Enter your current measurement and unit of volume: -13 o Error! You entered a negative number.

Enter your current measurement and unit of volume: 13 a

Error! Enter one of ’g’ for gallons, ’q’ for quarts, ’p’ for pints, ’c’ for cups, or ’o’ for ounces.

Enter your current measurement and unit of volume: -13 a Error! You entered a negative number.

Error! Enter one of ’g’ for gallons, ’q’ for quarts, ’p’ for pints, ’c’ for cups, or ’o’ for ounces.

Enter your current measurement and unit of volume: 13 o

Enter your desired unit of volume: z

Error! Enter one of ’g’ for gallons, ’q’ for quarts, ’p’ for pints, ’c’ for cups, or ’o’ for ounces.