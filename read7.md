# Javascipts makes the web pages more interactive.
#### Javascripts allow youto access and modify the content while web pages is bieng veiwed in the broswer.
#### Its rely on :
1. Access the content of the page 
2. Modify the content of the page 
3. Program rules or instructions the browser can follow 
4. React to events triggered by the user or browser

# What is the script :
#### A script is a series of instructions that a computer can follow to achieve a goal.

## Writing  a script:
#### To write a script, you need to first state your goal and then list the tasks that need to be completed in order to achieve it.  becuase the computeres are different from human thinking, you need to make flowchart so  your instructions must let the computer  solve the task programmatically.

# Different type of instructions :
1. expressions : Result in single value<br>
(i.e) var area = 3 * 5;<br>
(i.e) var color = 'white';

2. OPERATORS :Expressions rely on things called operators; they allow programmers to create a single value from one or more values. <br>
(i.e){= , < , && ,...} <br>

3. ARITHMETIC OPERATORS : Mathematical operators, which you can use with numbers. <br>
(i.e) {+,-,/,* , ++ , -- , %}<br>

4. STRING OPERATOR:<br>
(i.e) {**'**}<br>
If you want to jion two strings which each others just use this **+**.

MIXING NUMBERS AND STRINGS TOGETHER :<br>

When you place quotes around a number, it is a string (not 
a numeric data type), and you cannot perform addition 
operations on strings. <br>
var  costl  = '7'; <br>
var cost2 = '9 ' ; <Br>
var total = costl + cost2;<br> 
You would end up with a string 
saying '79'. <br>

If you try to add a numeric data type to a string, then the number becomes part of the string, e.g., adding a house number to a street name: <br>
var number  = 12; <br>
var  street= 'Ivy Road';<br> 
var add = number  + street; <br>
You would end up with a string 
saying '12Ivy Road'. <br>

If you try to use any of the other arithmetic operators on a string, then the value that results is usually a value called **NaN**. ***This means "not a number."***<br>
var score= ' seven'; <br>
var score2 = ' nine'; <br>
var total = score * score2;<br> 
You would end up with the value **NaN**. <br><br>


# Functions :<br>
Functions let you group a series of statements together to perform a specific task.
## To creat a function :
### Function decleration:
* type "function".
*  Give it a name  and then write the statments needed to achieve its tasks inside curly braces
### Calling function :
Just type its name e.g `sayHello()`

### Some functions need specific informatio e.g<br>
` function getArea (width, height){}....`<br>
### When you need to call such functions you need to declare the information e.g<br>
` function getArea (3, 5){}....`<br>

## Return a single value from function :<br>
` function calculateArae (width, height) {`<br>
`var area = width * height;`<br>
`return area ;`<br>
`}`<br>
`var wallOne = calculateArae(5,6) ;`<br>
`var wallTwo = calculateArae(10,15) ;`<br>

