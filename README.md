Download Link: https://assignmentchef.com/product/solved-operating-systems-laboratory-cs39002-assignment-1
<br>
<strong>Assignment 1: </strong>Familiarization with Unix system calls on process creation and management

<strong>1a.</strong>  Write a program in C/C++ under the Linux environment that would perform the following:

<ul>

 <li>Create five processes A, B, C, D, and E.</li>

 <li>The processes A, B and C will each generate 50 pseudo-random non zero integers. The processes A and B will forward the numbers in sorted order to process D (through pipes). The process C will forward the numbers in sorted order to process E (through pipes).</li>

 <li>The process D will read the numbers received from the two pipes in sorted order, merge them, and forward the numbers in sorted order to process E (through pipes).</li>

 <li>The process E will read the numbers received from the two pipes in sorted order, merge them, and print all the numbers in sorted order. Use pipes for inter process communication. ‐</li>

</ul>

<strong>1b.</strong>  Write a program in C/C++ under the Linux environment that would perform the following:

<ul>

 <li>In a loop, read a character string containing the name of an executable program with command line arguments, if any. ‐</li>

 <li>Fork a child process, and execute the program. o The loop will terminate if the command “quit” is entered.</li>

</ul>

<strong>Submission Guidelines: </strong>

<ul>

 <li>Create two separate programs for the two assignments, and name them</li>

</ul>

<strong>Ass1_&lt;groupno&gt;_1a </strong>and <strong>Ass1_&lt;groupno&gt;_1b </strong>(replace &lt;groupno&gt; by your group number).

<ul>

 <li>You must show the running version of the program(s) to your assigned TA during the lab hours.</li>

</ul>

<strong>Things to study: </strong>

<ul>

 <li>fork() system call</li>

 <li>pipe() system call</li>

 <li>execlp() / execvp() / execve() system call</li>

</ul>

<strong>Evaluation Guidelines: </strong>

Total marks for this assignment are 25. While entering marks, the partwise break up should also be entered according to the marking guidelines given below.




<table width="416">

 <tbody>

  <tr>

   <td width="359"><strong>Items for 1a</strong></td>

   <td width="56"><strong>Marks</strong></td>

  </tr>

  <tr>

   <td width="359">Process creation</td>

   <td width="56">8</td>

  </tr>

  <tr>

   <td width="359">Pseudo random number generation</td>

   <td width="56">5</td>

  </tr>

  <tr>

   <td width="359">Pipe creation</td>

   <td width="56">8</td>

  </tr>

  <tr>

   <td width="359">Reading from pipe</td>

   <td width="56">5</td>

  </tr>

  <tr>

   <td width="359">Writing to pipe</td>

   <td width="56">5</td>

  </tr>

  <tr>

   <td width="359">Merging of numbers</td>

   <td width="56">4</td>

  </tr>

  <tr>

   <td width="359"><strong>Total</strong></td>

   <td width="56">20</td>

  </tr>

  <tr>

   <td width="359"><strong>Items for 1b</strong></td>

   <td width="56"><strong>Marks</strong></td>

  </tr>

  <tr>

   <td width="359">Reading of arguments in a loop</td>

   <td width="56">5</td>

  </tr>

  <tr>

   <td width="359">Spawning the new processes using fork</td>

   <td width="56">5</td>

  </tr>

  <tr>

   <td width="359">Passing the command line arguments to the new process</td>

   <td width="56">5</td>

  </tr>

  <tr>

   <td width="359"><strong>Total</strong></td>

   <td width="56">15</td>

  </tr>

 </tbody>

</table>


