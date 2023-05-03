Download Link: https://assignmentchef.com/product/solved-cs212-lab-5-file-input-and-command-line-arguments
<br>
<span class="kksr-muted">Rate this product</span>

File input and command line arguments.

<ol>

 <li>Copy your Lab4Program1.java file to Lab5Progam1.java. Since the file name is different, change the name of the class to Lab5Program1.The program from Lab 4 initialized the array of words by an assignment statement. Modify the program so that it will read from a file, and the name of the file is given as a command line argument. For example, if the name of the input file is lab5input.txt, you would run the program using:<pre>     c:&gt;java Lab5Program1 lab5input.txt</pre>As you learned from reading the tutorial, each command line argument is stored in the String array of the main method (“args[]”). If the line above is used to run the program, args[0] should contain the String “lab5input.txt”.In the PowerPoint lecture on Arrays (available on Blackboard) you were shown a program that uses the TextFileInput class to read from a file. Make sure that this class is in your current directory (the same directory as Lab5Program1.java) so the run time JVM can find it.</li>

 <li>Use an editor, such as Notepad, to create the file lab5input.txt in the same directory as your program. You may use the words in the original array of Lab4Program1, or any other words you want.</li>

 <li>Put a method similar to the inputFromFile method you saw in the PowerPoint that will read each word from the input file and put it into a String array.</li>

 <li>Run your program and see that it runs the same way as the lab 4 program, and show your lab instructor.</li>