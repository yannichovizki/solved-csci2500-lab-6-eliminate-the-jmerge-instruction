Download Link: https://assignmentchef.com/product/solved-csci2500-lab-6-eliminate-the-jmerge-instruction
<br>
<strong>: </strong>For the first checkpoint, download the bit.s MIPS code example from the lec-10-05 folder on Submitty. Understand how the code works to produce the output below:

————–x—————–

-x———–xxx—————-xx———-x–x————–x–x———x—x————-x—x——–x—x————-x—-x——-x—-xxxxxx——-x—–x——x———-xx—–x——xx—x–xx——–xxxxxxx—–x—xx–xxxx————xx -x—x—xx—-xx———xxxxx-

–x–x–x—x—–x—xxxx-x——x-x-x————–xxxx-x—xxx–xx———xxxx——x—-x—x–x———xx—-x–x—–x—x-x—————–x——

–x–x-x—————-xx——

—x-xx——————-xx—-

—-xx—————–xx—x—

—-x—————–x–x—x–

—x—————–x—-xxxx–

–x——————-x———

–x——————–x——–

–x—–xxxxxxxx——-x——–

—x–xx——–xx—-x———

—x–x———–x—-xx——-

–xxxx————-xxxxxxxx—–

Modify the given code to eliminate the “jmerge” instruction in the printbit procedure. In other words, revise the procedure to use only one branch instruction.

To receive credit for this checkpoint, you need to show both your code revision and successful output.

<ol start="2">

 <li><strong>Checkpoint 2: </strong>Similar to Checkpoint 1, revise the bitcount procedure in s to eliminate the beq instruction. More specifically, you can only use the one bne instruction and the one jal instruction; no other branch or jump instructions are allowed.</li>

</ol>

Try running your code using the hexadecimal words shown in the lab06a.txt and lab06b.txt files available in Submitty.

And to test, add a syscall to print_int to display the return value (i.e., temporary register $t0) before you print the newline and return.

To receive credit for this checkpoint, you need to show both your code revision and successful output.

<ol start="3">

 <li><strong>Checkpoint 3: </strong>For the third checkpoint, make a copy of the revised s code, then modify this code as described below.</li>

</ol>

Currently, this code displays each 32-bit word of the given data on a line by itself, i.e., one word per line. Extend the bitcount procedure to display <em>n </em>words per line, where <em>n </em>is specified as the third argument to bitcount in register $a2.

Test your code by setting $a2 to 1. Then test your code using the lab06b.txt file with $a2 set to 2. What does your output look like?

As above, to receive credit for this checkpoint, you need to show both your code revision and successful output.