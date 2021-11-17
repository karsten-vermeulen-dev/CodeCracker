## Use functions to create the following:

<b>1.</b> Write a <i>Stars()</i> function which prints out a line of stars. Use a loop within the function if you know how. The number of stars in the line is given as a parameter. So, your function signature is: <br>

```cpp
void Stars(int numStars);
```

<b>2.</b> Write a <i>Rectangle()</i> function, which draws a rectangle of stars. Use a loop here too, if you can. This function should take two parameters, one for width, and one for height. <br>

```cpp
void Rectangle(int width, int height);
```

3. Write a HollowRect() function, which only draws the rectangle outline. Do this iteratively.
4. Write a Triangle() function that displays rows of stars, each row larger than the previous. Make sure the parameter passed reflects the amount of rows required.
5. Now try write a HollowTri() function, whereby only the triangle outline is drawn.
6. Write a Diamond() function, which renders rows of stars, each row larger than the previous. After the largest row has been rendered, draw smaller rows again. Pass in a parameter that determines how large the longest row should be.
7. Can you modify the Diamond() function to draw a roughly circular shape?

<b>1.</b> Create an application that requests the user to enter two different numbers and store them in variables. <br>
<b>2.</b> Using a menu, ask the user what they would like to do with the numbers, i.e. <i>add</i>, <i>subtract</i>, <i>multiply</i> or <i>divide</i> and store their choice as a numeric value or a symbol in a <i>char</i> variable. <br>
<b>3.</b> Check that only valid options are made. For example, if there are four options and the user selects a <b>6</b>, the menu should ignore that request or produce an error message. If you are using character symbols, make sure only valid symbols are input, i.e., '<b>+</b>', '<b>-</b>', '<b>x</b>', and '<b>/</b>'. <br>
<b>4.</b> Use <i>if/else-if/else/switch</i> statements to branch off and perform the operations. If you are familiar with functions, make sure that each operation is performed by its own function. <br>
<b>5.</b> Make sure that the menu system runs within a loop. As soon as an option has been made, and the numbers have been processed, make sure to return to the main menu. Keep the menu system running until the user chooses to exit the application. <br>
<b>6.</b> Add an option to calculate the remainder of a division. <br>
<b>7.</b> Make sure no errors occur when dividing by zero. <br>
<b>8.</b> Add <i>ASCII</i> art to make the menu and application look nicer.
