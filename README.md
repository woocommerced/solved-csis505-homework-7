Download Link: https://assignmentchef.com/product/solved-csis505-homework-7
<br>
<strong>Overview</strong>

In this module/week’s homework assignment, you will complete 2 exercises that will allow you to practice your skill on the topics of generic collections, lambdas, and streams that you learned about in the Reading &amp; Study material for this module/week.

<strong> </strong><strong>Instructions</strong>

<ol>

 <li>Refer to the Homework Grading Rubric before you begin this assignment.</li>

 <li>Complete the detailed instructions for each exercise included in the sections below. For each exercise, begin with a new Java project.</li>

 <li>As you write your code, provide all pertinent documentation in the form of JavaDoc comments for all classes and methods.

  <ol>

   <li>All class-level comments must include a description of the class along with your name and links to any outside resources you used (other than the textbook) while writing your code.</li>

   <li>Each method must also have a comment that indicates the purpose of the method and, if applicable, the purpose of all parameters and return value.</li>

   <li>Additional in-line comments must be used to explain complex algorithms or unique solutions to the problem.</li>

  </ol></li>

 <li>Print, sign, and scan (or take a photo of) the Pledge of Academic Integrity.</li>

 <li>After you have completed the exercises for this assignment, submit the following via the Blackboard submission link: a digital copy of your signed pledge sheet, a compressed folder containing your code, and any additional written requirements specified below. <strong>Failure to submit a signed pledge of academic integrity for this assignment will result in an automatic grade of zero (0) for this assignment</strong>.</li>

</ol>

<strong>Exercise 1</strong>

Modify the List&lt;T&gt; class of Figure 21.3 in the textbook to include a method that recursively searches a linked-list for a specified value. <strong>Ensure that the name of your method includes your last name</strong>. The method must return a reference to the value if it is found; otherwise, it must return null. Use your method in a test program that creates a list of integers. The program must prompt the user for a value to locate in the list.

<strong>Exercise 2</strong>

As presented in the textbook, linked-lists must be searched sequentially. For large lists, this can result in poor performance. A common technique for improving list-searching performance is to create and maintain an index to the list. An index is a set of references to key places in the list. For example, an application that searches a large list of names could improve performance by creating an index with 26 entries—one for each letter of the alphabet. A search operation for a last name beginning with ‘Y’ would then first search the index to determine where the ‘Y’ entries began, then go to the list at that point and search linearly until the desired name was found. This would be much faster than searching the linked list from the beginning. Use the List class of Figure 21.3 in the textbook as the basis for an IndexedList class that implements the approach described above. Write a program that demonstrates the operation of your IndexedList class.


