Download Link: https://assignmentchef.com/product/solved-cosc117-homework2-more-calculations
<br>
<h1>1             Exercises</h1>

For each of the following create a new project with an appropriate name and then write a program that solves the given problem.

Remember:

<ul>

 <li>Shift+Ctrl+F to format the program, or Shift+Command+F on the Mac.</li>

 <li>The standard comments of at the top,

  <ul>

   <li>Name</li>

   <li>Date</li>

   <li>Description</li>

  </ul></li>

</ul>

For each program, you will be submitting the java code file through MyClasses, as you did before. I also want either a Microsoft Word docx file, LibreOffice Writer odt, or a text file (which you can create with NotePad++) which contains,

<ul>

 <li>The answers to the three main questions:

  <ol>

   <li>What do I want as the final result of the program? (WANT)</li>

   <li>What is the calculation I will need to do? (HOW) 3. What do I need to complete this calculation? (NEED)</li>

  </ol></li>

 <li>The answers above reformatted into an algorithm.</li>

 <li>Output of at least three runs of each program on different data inputs.</li>

</ul>

This docx, odt, or text file is to be uploaded to MyClasses as well. You can copy and paste output from the Eclipse console area to the word or text program.

<h2>1.1           Programming Exercises</h2>

<ol>

 <li>Write a program that will take four numeric inputs from the user and return the maximum and the minimum of the inputs. To do this we will use a technique that we will generalize later. First of all, we could do this with conditional statements (sometimes called if statements) but that is not needed and do not use them for this exercise. Recall that the Math command has a function called max that finds the maximum of two numbers, unfortunately it does not take 4 numbers or this would be a very short program. As a test, write a program that just takes in two numbers num1 and num2, does the line below and then prints out the value of max. Run it a few times with different inputs to get a feel for how it works.</li>

</ol>

<strong>double </strong>max = Math.max(num1, num2);

Now use the max function with the value of max and num3 and assign the result back into max, do that again with the values of max and num4. Finding the minimum of the four numbers is similar since Math also has a min function.

Input number 1: 127 Input number 2: 45

Input number 3: 278

Input number 4: 97

Maximum = 278.0

Minimum = 45.0

<ol start="2">

 <li>In the game of Dungeons and Dragons the dice that are used are the five platonic solids, one has 4 faces, one has 6 faces, one has 8 faces, one has 12 faces, and the final one has 20 faces. Write a program that will simulate the rolling of the five dice and print out the results in the above order.</li>

 <li>Write a program that will calculate the area of a trapezoid.</li>

</ol>

The area of a trapezoid is calculated as the height <em>m </em>times the average of the two bases <em>k </em>and <em>f</em>.

Input one side length: 4

Input the other side length: 7

Input the height: 3

Area = 16.5

<ol start="4">

 <li>In the game of Black Jack each player is dealt two cards from a standard poker deck, face down. In a standard poker deck of cards, each card has a face value and a suit. The face values are A (Ace), 2, 3, 4, 5, 6, 7, 8, 9, 10, J (Jack), Q (Queen), K (King) and the suits are &#x2666; (Diamonds), &#x2665; (Hearts), &#x2663; (Clubs) and &#x2660; (Spades). Write a program that will “deal” two cards to two players and output something similar to the following.</li>

</ol>

Player 1

Card 1: 7 of 2

Card 2: 1 of 3

Player 2

Card 1: 7 of 1

Card 2: 12 of 3

In this output the first number is the face value, with Ace = 1, Jack = 11, Queen = 12 and King = 13. The other numbers of the face value are, of course, the number on the card. The second number is the suit with Diamonds = 1, Hearts = 2, Clubs = 3 and Spades = 4. Make sure that you test the program several times to make sure that all of your values are in the correct ranges. It is possible that the same card may be dealt more than once, that is, the 3 of clubs could show up several times. Do not worry about this.

<h1>2             Challenge Exercise</h1>

Challenge Exercises are optional, they will be graded as extra credit.

<ol>

 <li>In a regular octagon, pictured below, the length <em>r </em>is the length from the center of the octagon to one of the vertices, <em>h </em>is the perpendicular length from the center to one side, and the length of one side is <em>S</em>.</li>

</ol>

The side length <em>S </em>can be calculated as <em>r</em>·<sup>p</sup>2 −         2. The length <em>h </em>can be calculated as

. The area of the triangle with sides <em>h </em>and <em>r </em>can be calculated as , where <em>b </em>is half of <em>S</em>. There are 16 of these triangles inside the octagon and of course there are 8 sides.

Write a program that will take the length <em>r </em>and calculate the area of the octagon and the perimeter (total distance around) of the octagon. A sample output is below.

Input r: 5

Area = 70.71067811865474

Perimeter = 30.614674589207176