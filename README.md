#DIV Students and Graduates Training Programs
<h3>Week 1 - 3 Submission - Martha Teye</h3>

<p>Try out all the 3 questions <a href="https://marthateye.github.io/divAss/index.html">here</a><p>

<h4>Week 1: Write a JavaScript program that accept two integers and display the larger integer.</h4>

<p>The program first checks if the numbers entered are integers or not.</p> 
<p>If number is not an integer the user is alerted.</p>
<p>If number is integer, the comapre function would be called.</p>
<p>Then it finds the larger number using if statements amongst the two integers provided</p>

<h4>Week 2: Write a JavaScript for loop that will iterate from 0 to 15. For each iteration, it will check if the current number is odd or even and display a message to the screen.</h4>
<p>In this question, the modulus 2 of a number is calculated. </p>
<p>The number that returns 0 shows that it is an even number.</p>
<p>Numbers within the range that return 1 when the mod 2 is calculate is termed as odd.</p>

<h4>Week 3: Write a Hash Table class that stores strings in a hash table, where keys are calculated using the first two letters of the string.</h4>
<p>First, the program accepts strings(value) and creates a substring of the first two letters of the string which would be used as it's key.</p>
<p>In indexing them in the hash table, I used the sum of ASCII character representation value multiplied by the position of the string.</p>
<p>For instance, if my input string was "new", the key would be "ne"</p>
<p>And the index would be calculated as follows: n=110, e=101, w= </p>
<p>So since this is a three word string, their index would be (110*1 + 101*2 + 119*3) mod 2069</p>
<p>This would give an index of 669
<p>The prime number 2069 was used because it reduces the possibility of collisions </p>
<p>For details about the hash function and collision handling techniques, please refer to index.html</p>
