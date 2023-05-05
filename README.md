Download Link: https://assignmentchef.com/product/solved-cse102-homework-4
<br>
<ul>

 <li>Write a C code which does the following:</li>

 <li>Your program will read a file named <sub>txt</sub></li>

 <li><sub>txt </sub>contains single line text. The text describes a tree structure. It follows the <sub>Newick </sub>format rules. But there are simplifications and/or modifications:

  <ul>

   <li>Each node is represented by a single character. They are separated by <sub>comma</sub>. Branching is described by matching parentheses.</li>

   <li>The length of the text will not be greater than <sub>250</sub></li>

  </ul></li>

 <li>Below is an example of a tree description:</li>

</ul>

(A,(c,B,e),K,D,e,(f,(d,F))) • This tree can be visualized as follows:

-A

–c

–B

–e

-K

-D

-e

–f

—d

—F

<ul>

 <li>Another example:</li>

</ul>

(A,(A,A,(A),A),A)

<ul>

 <li>Visualization:</li>

</ul>

-A –A

–A

—A

–A

-A

<ul>

 <li>Another example:</li>

</ul>

A,(A,A,(A),A),A

<ul>

 <li>Visualization:</li>

</ul>

A

-A

-A

–A

-A

A

<ul>

 <li>Your program will read the simplified newick formatted tree description from a file and write the visualization of the described tree to <sub>txt</sub>.</li>

 <li>Core part of your implementation (parsing and creating visualization) should utilize <strong><sub>recursion </sub></strong>otherwise you will get <sub>0pts</sub>. For this problem, coding without recursion is significantly easier.</li>

 <li>Pay attention to the structure of the output. If your program prints something slightly different or anything extra, you will loose at least <sub>30pts</sub>. Don’t print any debug messages or greeting texts. Don’t add extra spaces, newlines, commas etc…</li>

</ul>

<strong>Turn in:</strong>

<ul>

 <li>Source code of a complete C program. Name of the file should be in this format: <sub>&lt;full_name&gt;_&lt;id&gt;.c</sub>.</li>

 <li>Example: <sub>c</sub>. Please do not use any Turkish special characters.</li>

 <li>You don’t need to use an IDE for this assignment. Your code will be compiled and run in a command window.</li>

 <li>Your code will be compiled and tested on a Linux machine(Ubuntu). GCC will be used.</li>

 <li>Make sure that your program does not require specific encodings/markings/line-ending-chars. Make sure it works with a file created in a linux environment.</li>

 <li>Make sure you don’t get compile errors when you issue this command : <sub>gcc &lt;full_name&gt;_&lt;id&gt;.c</sub>.</li>

 <li>A script will be used in order to check the correctness of your results. So, be careful not to violate the expected output format.</li>

 <li>Provide comments unless you are not interested in partial credit. (If I cannot easily understand your design, you may loose points.)</li>

 <li>You may not get full credit if your implementation contradicts with the statements in this document.</li>

 <li>If your program requires additional compile and link options, state that requirement at beginning of your source code as a comment.</li>

</ul>