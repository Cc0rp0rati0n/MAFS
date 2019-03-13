<p align="center">
  <h1>Introduction / Getting started</h1><br><br>
</p>

MAFS is a programing language that uses variables and mathematical operators (that's what M stands for) to run.

<p align="center">
  <b><h2>Starting a program:</h2></b>
</p>

MAFS is a cart / code loader which means that you can edit and write code wherever you want (even in notepad)
On the start there's something called <em>variable defining</em> . That means that you write the starter values of variables.
The best way to show you will be an example:
~~~~
24 
36 
_ 
(add: 1 2 ) 
print= 1 / 
~~~~
If you don't know what anything of this means, you are not the only.
So, back on track, section 24 36 _ is variable defining.
- 24 represents the first variable
- 36 represents the second variable 
- _ **represents the end of variable defining and starts behaviour**

*Underscore always represents the end of variable defining and starts behaviour*

***NOTE: ALWAYS PUT A SPACE AFTER A LINE, AFTER VARIABLE DEFINING AND BEHAVIOUR***

<p align="center">
  <b><h2>Basic Commands:</h2></b>
</p>
<p align="center">
  <b> print= </b><br>
  <em> Print= command is used to print out variables on the screen. </em>
</p>
~~~~
hello_world! 
hello_test 
_ 
print= 1 2 / 
~~~~

It printed: HELLO WORLD! HELLO TEST

From an example you can see that it doesn't print the value you put in, but number of *variable* you put in.
Here's another example:
~~~~
pizza 
spageti 
ravioli 
mama_mia 
_ 
print= ! ran / 
~~~~

It will printone of these:
- PIZZA
- SPAGETI
- RAVIOLI
- MAMA MIA

So, now we're going to use **SPECIAL FUNCTIONS** <br>
It sounds badass, because it is (jk, this is still in basic commands)

Code reader will know when to use these special functions, because there is always **!** before them
***NOTE: FUNCTIONS ARE NOT IN TYPE !FUNCTION, BUT ! FUNCTION***

Cheatsheet of functions:
- ran *puts random variable*
- fromTo *puts random variable of specific range* 
- numOfChars *number of characters in the variable* 
- newLine *goes to a new line* <br>
*! newLine can be replaced with ~ in the text itself. Example:*
~~~~
bob:,,i_love_hamburgers!"~ross:,,yeah_me_too" 
_ 
print= 1 / 
~~~~
Prints: <br>
BOB:,,I LOVE HAMBURGERS!" <br>
ROSS:,,YEAH  ME TOO"

***OTHER NOTES:***<br>
***TO FINISH THE PRINT= COMMAND TYPE "/" (DON'T FORGET A SPACE)***<br>
***PRINT FUNCTION DOESN'T PRINT UNDERSCORES***
<br>
<p align="center">
  <b> getInput </b><br>
  <em> GetInput command is used to store th text player typed. </em>
</p>
<br>
I think definition speaks for itself, but i will give you an example
~~~~
number_one? 
number_two? 
_ 
print= 1 / 
getInput 
print= 2 / 
getInput 
(calc: 3 ; 4 ) 
print= 3 / 
~~~~
So here you can see that **getInput** creates a new variable which is equal to a thing you typed in the input box.
<br>
<p align="center">
  <b> stop </b><br>
  <em> Stops the whole game. </em>
</p>
<br>
<p align="center">
  <b><h2>Variable / Mathematical Commands:</h2></b>
</p>
<p align="center">
  <b> (if: cn x y z w ) </b><br>
  <em> Goes to z element if something is true. Goes to w element if it's false.</em>
</p>
<br>

cn is replaced with ***command name***
(command name can be:
equal
notEqual
)

equal: Goes to z element if x is equal y. Goes to w element if else.<br>
notEqual: Goes to z element if x is **NOT** equal y. Goes to w element if else.
<br>
***Now, element isn't equal line***<br>
Let me show you what's an element:
~~~~
  print= 1 2 3 4 / 
    1    2 3 4 5 6 
~~~~
Got it?
<br>
<p align="center">
  <b> overwrite x y </b><br>
  <em> overwrites x variable with y VALUE.</em>
</p>
<br>
***VALUE IS VALUE LIKE "LOL", FOR EXAMPLE, WHERE VARIABLE IS 1="LOL"***<br>

Overwrite also has special functions ! ran and ! fromTo which work the same way.

<br>
<p align="center">
  <b> (add: x y ) </b><br>
  <em> overwrites x variable with y VALUE.</em>
</p>
