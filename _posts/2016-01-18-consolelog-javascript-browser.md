---
layout: post

#event information
title:  "Consolelog with the Browser Console"
cover: "https://raw.githubusercontent.com/bkimminich/juice-shop/master/app/public/images/JuiceShop_Logo.png"
date:   2016-06-15

#event organiser details
organiser: "Lucas Gatsas"


---
<h2 class="section-heading">Getting Started with Javascript.</h2>


What am I learning?
This is JavaScript (JS), a programming language. There are many languages, but JS has many uses and is easy to learn.

What can we use JavaScript for?

 make websites respond to user interaction
 build apps and games (e.g. blackjack)
 access information on the Internet (e.g. find out the top trending words on Twitter by topic)
 organize and present data (e.g. automate spreadsheet work; data visualization)

confrim method: 

{% highlight ruby linenos %}
confirm('This is an example of using JS to create some interaction on a website. Click OK to continue!');

{% endhighlight %}





<h2 class="section-heading">What is programming?</h2>
Programming is like writing a list of instructions to the computer so it can do cool stuff with your information.

Programs can't yet make your bed, but they can do math, keep track of your bank account, or send a message to a friend.

To do any of these actions, the program needs an input. You can ask for input with a prompt.

Examples:

{% highlight ruby linenos %}
prompt("what is your name?");
prompt("my name is Lucas Gatsas");
{% endhighlight %}


<h2 class="section-heading">
Data Types I & II: Numbers & Strings</h2>


Data comes in various types. You have used two already!

a. numbers are quantities, just like you're used to. You can do math with them.

b. strings are sequences of characters, like the letters a-z, spaces, and even numbers. These are all strings: "Ryan", "4" and "What is your name?" Strings are extremely useful as labels, names, and content for your programs.

To make a number in your code, just write a number as numerals without quotes: 42, 190.12334.

To write a string, surround words with quotes: "What is your name?"


Write a string with at least 3 words. Check out the examples of strings above.
Find the length of the string by writing a period (full stop) and the word length, like this:

"string".length
Length counts every character in the string - including spaces!

"lucas are studying".length  = 18 types

3 words 



<h2 class="section-heading">Data Type III: Booleans</h2>


Nice job! Next let's look at booleans. A boolean is either true or false.

For example, comparing two numbers returns a true or false result:

23 > 10 is true
5 < 4 is false


Let's compare two numbers to return a true result:

First, write the string "I'm coding like a champ"
Next, find the length of the string using .length
Then, compare the string's length to see if it is greater than 10
If you want to check your code, click "Stuck? Get a hint!" below.

{% highlight ruby linenos %}
"Lucas is a great coder!".length > 9;
{% endhighlight %}


<h2 class="section-heading">Using console.log</h2>
You may have noticed that the interpreter doesn't print out every single thing it does. So if we want to know what it's thinking, we sometimes have to ask it to speak to us.

console.log() will take whatever is inside the parentheses and log it to the console below your code—that's why it's called console.log()!

This is commonly called printing out.




<h2 class="section-heading">Comparisons</h2>
So far we've learned about three data types:

strings (e.g. "dogs go woof!")
numbers (e.g. 4, 10)
booleans (e.g. false, 5 > 4)
Now let's learn more about comparison operators.

List of comparison operators:


{% highlight ruby linenos %}
  > Greater than

  < Less than

    <= Less than or equal to

    >= Greater than or equal to

  === Equal to

  !== Not equal to
{% endhighlight %}



{% highlight ruby linenos %}
// Here is an example of using the greater than (>) operator.
console.log(15 > 4); // 15 > 4 evaluates to true, so true is printed.

// Fill in with >, <, === so that the following print out true:
console.log("Xiao Hui".length < 122);
console.log("Goody Donaldson".length >  8);
console.log(8*2 === 16);
{% endhighlight %}


<h2 class="section-heading">Decisions, decisions</h2>
Nice work on comparisons! Now let's see how we can use comparisons to ask yes or no questions.

Say we want to write a program that asks whether your name is longer than 7 letters. If the answer is yes, we can respond with "You have a long name!" We can do this with an if statement:


{% highlight ruby linenos %}
if ("my name is lucas gatsas".length >= 7 ) {
    console.log("you have a long name");
}
{% endhighlight %}



<h2 class="section-heading">Computers are smart</h2>
Great! We used an if statement to do something if the answer to the condition was yes, or true as we say in JavaScript.

In addition to doing something when the condition is true, we can do something else if the condition is false. For example, if your name is shorter than 7 letters, we can respond with "You have a short name!" We can do this using an if / else statement:


{% highlight ruby linenos %}
if ("Lucas Gatsas".length >= 7 ) 
{
    console.log("Let's go down the first road!");
}
else 
{
    
    console.log("you are the code champion!")
    // What should we do if the condition is false? Fill in here:
    
}
{% endhighlight %}



<h2 class="section-heading">More practice with conditionals</h2>
Now let's practice using if/else statements. Do as much as you can by yourself, but if you need a reminder!


1. Write an if/else statement, just like we did in the last exercise. Here's what the outline of the code looked like:

2. If your condition is true, use console.log to print "The condition is true".

3. therwise (else) when it is false, use console.log to print "The condition is false".

4. Make sure your condition evaluates to false, so that your program prints out "The condition is false".


{% highlight ruby linenos %}



if (10 < 3)
{
     //if condition is true
     console.log("The condition is true");
     // do this code
}
else //"otherwise"
{
    console.log("The condition is false");

}
{% endhighlight %}



<h2 class="section-heading">Computers aren't that smart</h2>
Well done! Now, computers are very literal. Syntax needs to be in exactly the right place for the computer to understand the code.

As you get started with programming, we will teach you many syntax rules. This is sort of like the grammar of programming languages. Grammar first, then programming poetry!


There are many mistakes in this code. Find them and fix them all.

You are doing what's called "debugging," a term popularized by Grace Hopper when she literally removed a moth from her computer.

{% highlight ruby linenos %}
if (10 === 10) 
{
    console.log("You got a true!");
} else {
    console.log("You got a false!");
}
{% endhighlight %}



<h2 class="section-heading">Mid-lesson breather</h2>
We've covered a lot of ground so far! So many new terms, so much syntax. Let's take a breather and review. We have learned:

1. Confirm and prompt

We can make pop-up boxes appear! 
confirm("I am ok");
prompt("Are you ok?");

2. Data types

a. numbers (e.g. 4.3, 134)

b. strings (e.g. "dogs go woof!", "JavaScript expert")

c. booleans (e.g. false, 5 > 4)

3. Conditionals

If the first condition is met, execute the first code block. If it is not met, execute the code in the else block. See the code on the right for another example.



{% highlight ruby linenos %}
// This is an example of an if / else statement.

if (12 / 4 === "Ari".length) {
    confirm("Will this run the first block?");
} else {
    confirm("Or the second block?");
}
{% endhighlight %}


<h2 class="section-heading">Math</h2>
We saw basic math before. The basic math symbols we learned in school work here. Even the order in which the computer understands the math is the same as in school!

Code:

1. ( ): control order of operations
2. * and /: multiplication and division
3. - and +: subtraction and addition

Examples:

1. 100/10 evaluates to 10
2. "Jane".length + 5 evaluates to 9
3. 5*(3+1) evaluates to 20

Complete the missing bits of code to construct the if / else statement. Make the condition evaluate to true.
Finish the else statement by printing out the string "Error Error Error" to the console.

{% highlight ruby linenos %}
if ("Jon".length * 2 / (2+1) === 2)
{
    console.log("The answer makes sense!");
} 
else 
{
    console.log("Error Error Error");

}
{% endhighlight %}





<h2 class="section-heading">Math and the modulo</h2>
Let's meet an interesting symbol called modulo. When % is placed between two numbers, the computer will divide the first number by the second, and then return the remainder of that division.

So if we do 23 % 10, we divide 23 by 10 which equals 2 with 3 left over. So 23 % 10 evaluates to 3.

More examples:

17 % 5 evaluates to 2

13 % 7 evaluates to 6






Use console.log and modulo three times to print the remainder of the following equations:

a. 14 / 3

b. 99 / 8

c. 11 / 3




