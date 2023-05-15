# Learn-to-Code-Homework

0. In general, try to modify _any_ code you've written to add new features until you just can't add anything else.

1. Start with the guessing game. If it doesn't have a way for the user to quit the game, add that. (Perhaps entering a guess of 0 means the user is done playing.)
   
   A. Tell the player if they are "close" when they make their guess.   
   
   B. Keep track of all the guesses the user guessed. Keep the guesses in a list so that you can show the user their guesses at the end. Attached is a screenshot of how I think it should work. Be sure to write down the steps before writing any code! 
Here is the intended output:
<pre>
Enter your guess: 50
Too high!
Enter your guess: 25
Too high!
Enter your guess: 12
Too high!
Enter your guess: 6
Too high!
Enter your guess: 3
Too low!
Enter your guess: 4
Too low!
Enter your guess: 5
You got it in 7 guesses!
Here are your guesses: [50, 25, 12, 6, 3, 4, 5]
</pre>
   C. Limit the number of guesses to 10. After 10 guesses, tell them their guesses and the answer.

2. Start with the jumble "scrambled word" program and modify it so that only guesses which contain the same letters as the scrambled word are considered true guesses.

4. Write a Python program to print the numbers from 1 to 100 on a line by themselves...BUT, if the number is divisible by 3, you should write 'fizz' instead of the number, and if the number is divisible by 5, write 'buzz' instead of the number, and if it's divisble by both 3 and 5, write 'fizzbuzz', like so:
<pre>
    1
    2
    fizz
    4
    buzz
    fizz
    7
    8
    fizz
    buzz
    11
    fizz
    13
    14
    fizzbuzz
    16
    17
    ...
</pre>
