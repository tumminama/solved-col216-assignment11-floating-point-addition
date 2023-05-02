Download Link: https://assignmentchef.com/product/solved-col216-assignment11-floating-point-addition
<br>
In this assignment you will do a software implementation of the Floating Point Adder whose algorithm was covered in class, and is outlined in Figure 3.14 (Page 205 of the textbook). Assume that each of the boxes numbered 1, 2, 3, and 4 require one clock cycle, and the condition checks require zero time.

<strong>Inputs</strong> to the program will be:

<ol>

 <li>A text file with each line containing a pair of floating point numbers to be added, in binary representation (a string of ‘0’ and ‘1’ characters in the file). See sample below.</li>

</ol>

<strong>Outputs</strong> from the program will be:

<ol>

 <li>A sequence of addition results, each line containing one result (a string of ‘0’ and ‘1’ characters) and the number of clock cycles required for performing the addition.</li>

</ol>

<strong>Deliverables</strong>:

<ol>

 <li>Software implementation of the floating point adder referred to above.</li>

 <li>Test files used to verify your program. Remember to test for special cases such as Overflow, Underflow, Normalised result, etc.</li>

 <li>A document explaining the different test cases.</li>

</ol>

<strong>Sample Input File (each line contains the representation for 2 floating point numbers, both 32 bits wide)</strong>:

11001100110011001111110011001100 11001100110011001111110011001100 01001110110011001111110011001101 11001100110111001101110011001110

<strong>Sample Output File (just examples. These are not be the computed outputs for the above input file)</strong>:

11001110110011001111110011001101 01001110110011001111110011001101 4