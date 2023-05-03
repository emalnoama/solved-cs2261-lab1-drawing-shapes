Download Link: https://assignmentchef.com/product/solved-cs2261-lab1-drawing-shapes
<br>
Drawing Shapes

<strong>Provided Files</strong><strong>  </strong>

<ul>

 <li>lab01.c</li>

</ul>

<h1>Files to Edit/Add</h1>

<ul>

 <li>c</li>

 <li>Makefile</li>

 <li>.vscode tasks.json</li>

</ul>




<h1>Instructions</h1>

Note: Make sure to copy over your Makefile and .vscode/tasks.json from Lab00.

In this lab, you will be completing TODOs to finish writing three functions:

<ul>

 <li><strong>TODO 1.0-1.1</strong></li>

</ul>

void setPixel(int col, int row, unsigned short color)

<ul>

 <li>Fills the pixel at the specified col and row with the specified color</li>

</ul>

<ul>

 <li><strong>TODO 2.0-2.1 </strong></li>

</ul>

void drawRect(int col, int row)

<ul>

 <li>Draws a rectangle at the specified column and row</li>

</ul>

○ MUST BE FILLED IN (i.e. a solid rectangle, not just lines)

○ May be any color

○ May be any (GBA appropriate) size

○ May NOT be hardcoded. You may not just call setPixel for every colored-in dot on your rectangle. You must use iteration to do so!

<ul>

 <li><strong>TODO 3.0-3.1 </strong></li>

</ul>

void drawTriangle(int col, int row)

<ul>

 <li>Draws a triangle at the specified column and row</li>

</ul>

○ May be any color, either filled in or not (your choice)

○ May be any (GBA appropriate) size

○ May NOT be hardcoded. You may not just call setPixel for every colored-in

dot on your triangle. You must use iteration to do so!

After writing the two functions, ​<strong>call the </strong>​<strong>drawTriangle </strong>​<strong>function two times and call the drawRect function one time in your main function,</strong>​ with different parameters. The output of your program should look something like the following.







Your triangles and your rectangle may be any size, shape, color, rotation, or position you want, as long as we can see that you drew two triangles and one filled-in rectangle. If you want, you can add parameters to the function to control color, size, or shape. After you have completed all the TODOs and your output looks correct, you are finished with the lab after you submit it.

<strong> </strong>

<h1>Tips</h1>

<ul>

 <li>For-loops are really great for drawing lines</li>

 <li>The GBA screen size is 240 pixels wide and 160 pixels tall</li>

 <li>If you add parameters to your ​drawLetter ​function, you must change its prototype</li>

 <li>If you add parameters to your ​drawRect ​function, you must change its prototype</li>

</ul>


