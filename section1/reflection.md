## Section 1 Reflection

### 1. Regarding the blog posts in Part A, how do you feel about asking questions? Do you tend to ask them too soon, or wait too long, or somewhere in between?

I am extremely comfortable asking questions.  As an educator, I know how important it is to know when you don't know and I have no shame in admitting I don't understand/need clarification.

### 2. What are the data types you learned about in this section? In your own words, define each.

The *3 types* I learned about are String, number, and boolean.  
I honestly think about these as the 3 types of answers to a math test.

1. `String` is like your written response questions.  Strings go in quotes and will print in the log exactly as you typed it in the quotation marks.  The values you put in strings can be anything (numbers, characters, words, etc.) as long as they are in quotes the computer will treat it as a `string`

2. `Numbers` are like the problems on a math test that just require a number answer.  These do not need to be in quotes and just represent a number value.  decimals, whole numbers, and negative numbers are examples.

3. `Boolean` is like a true false question on a math test.  "does the x value satisfy the inequality?  yes or no?"

### 3. How would you log the string `"Hello World!"` to the console?

`console.log("Hello world!");``

### 4. What is/are the character(s) you would use to indicate comments in a JavaScript file? What is the purpose of a code comment?

To indicate comments in JavaScript one would use two forward slashes``//``

Code comments can be used to describe or annotate what a certain block of code does .  This can be helpful to myself or my teammates who might be reviewing/editing or adding code.

```JavaScript
//declares the initial condition of the IF statement.
if (percentBatteryLeft >= 15) {}
```   

The double forward slash can also be used to omit a block of code that follows.  This can be useful when debugging/testing code.  It "silences" the code.

### 5. In your own words, what is a variable? How would you explain it to a 5 year old?
A variable is something that can change.  Things that vary from day to day?  The temperature outside, the money in someones pocket.
in code we can name things like temperature and then give it a value (like the degrees in Fahrenheit.  

  **Example:**
   In a text editor I can create a variable for temperature by saying
  `var` (this tells the computer that I am making a variable) and then I want to name it dailyTemp and give it a value (any of the 3 data types mentioned above).

  ```JavaScript
  var dailyTemp = 72;
```
### 6. Think of a site or app you use frequently. What are three variables that are probably used? Which data type would each of those variables probably hold?

Google calendar would use a lot of number variables (keeping track of dates and specific times) and boolean (is it after 3:30 pm?  if `true` notify user that it is time to begin homework).  Google calendar also uses strings when you add titles and tasks.  Whatever you type in to the title or task box is what populates on your calendar.

### 7. In your own words, explain what concatenation is.
Combining variables and strings together using the + operator.

Example:
```JavaScript
var names = ["Sevy", "Lindsey", "Jericho", "Raeonna", "Latrina", "Jhana", "Luca"];
for (var i = 2; i < names.length; i++){
  console.log("Happy Birthday, " + names[i] + "!");
}
```
Here the the console.log will print the strings "Happy Birthday" and "!" around the variable names[i].

### 8. Think of a site or app you use frequently. Where do you think the developers used concatenation?
When a website greets you when you log into your username.  

The code probably looks like

`console.log("Welcome " + userName[i] + "!");``

### 9. What questions do you still have about the work we've done so far? (not having a question is not an option)

1. What are other data types we can use?

2. Is an array a data type?

3. Is interpolation or concatenation more often used?  
