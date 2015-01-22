**Unit 2: Introduction to Stacks and Queues** <span id="2"></span> 
*This unit will introduce you to two basic Data Structures—Stacks and
Queues—and identify the operations that must be provided with each Stack
and Queue implementation.  Students will also learn how arrays and
circular arrays can be used to implement a Stack and a Queue and discuss
the advantages and disadvantages of their use.*

**Unit 2 Time Advisory**  
This unit will take you approximately 3 hours to complete.  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 2.1: 1.5 hours  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 2.2: 0.5 hours  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 2.3: 1 hour

**Unit2 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:
-   Describe the design and implementations of Stacks and Queues.
-   Identify the operations associated with the implementations of
    Stacks and Queues.  

**2.1 Introduction to Stacks** <span id="2.1"></span> 
-   **Reading: Oracle Think Quest Education Foundation’s “Stacks”**
    Link: Oracle Think Quest Education Foundation’s
    “[Stacks](http://wayback.archive-it.org/3635/20130722193840/http://library.thinkquest.org/C005618/text/stacks.htm)”
    (HTML)  
        
     Instructions: This reading covers subunits 2.1.1. through 2.1.3 and
    their respective subunits, where applicable.  Please read the
    information provided in the above link in its entirety.  
      
     This reading should take you approximately 30 minutes to
    complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Lecture: IIT Delhi Course on Data Structures and Algorithms: Dr.
    Navin Garg’s “Lecture 2: Stacks”**
    Link: IIT Delhi Course on Data Structures and Algorithms: Dr. Navin
    Garg’s “[Lecture 2:
    Stacks](http://www.youtube.com/watch?v=g1USSZVWDsY)”  
      
     Instructions: Please click the link above and view the video in its
    entirety (1:04:10) to gain an understanding of stacks.  This lecture
    covers subunits 2.1.1 through 2.1.3 of this unit.      
      
     This lecture should take you approximately 1 hour to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.1.1 Stack Operations** <span id="2.1.1"></span> 
*This subunit is covered by the “Stacks” reading listed in subunit 2.1
above.  You should read the article in its entirety to get a good
understanding of basic operations on a stack, such as the* empty*, the*
push*, and the* pop*.  This subunit is also covered in the first half of
the video lecture “Lecture 2: Stacks” listed in subunit 2.1 above.  A
stack is characterized by two fundamental operations, called “push” and
“pop.”  The push operation adds a new item to the top of the stack, or
initializes the stack if it is empty.  The pop operation removes an item
from the top of the stack.  We will study how to implement these stack
operations.*  
  
 This reading should take you approximately 30 minutes to complete.

**2.1.2 Stack Elements** <span id="2.1.2"></span> 
*This subunit is covered by the “Stacks” reading listed in subunit 2.1
above.  You should read the article in its entirety to get a good
understanding of elements of a stack that are used in basic operations,
such as the* empty*, the* push*, and the* pop*.  This subunit is also
covered in the first half of the video lecture “Lecture 2: Stacks”
listed in subunit 2.1 above.  Earlier, we looked into abstract data
types.  A stack can have any* *[abstract data
type](http://en.wikipedia.org/wiki/Abstract_data_type "Abstract data type") as
an* [*element*](http://en.wikipedia.org/wiki/Element "Element")*.  This
subunit covers how the elements of a stack can be implemented and used
in the stack operations discussed above.*  
  
 This reading should take you approximately 30 minutes to complete.

**2.1.3 Stack Construction** <span id="2.1.3"></span> 
*This subunit is covered in the second half of the video lecture
“Lecture 2: Stacks” listed in subunit 2.1 above.  A stack typically has
a small number of operations performed on it.  The nature of the pop and
push operations mean that stack elements have a natural order.  Elements
are removed from the stack in the reverse order to the order of their
addition; therefore, the lower elements are those that have been on the
stack the longest.  All of these are important aspects of stack
construction.*  
  
 This reading should take you approximately 30 minutes to complete.

**2.2 Array-Based Implementation of a Stack** <span id="2.2"></span> 
-   **Reading: University of Texas – San Antonio: Professor Wagner’s:
    “Stacks: C, C++, and Java Side by Side”**
    Link: University of Texas – San Antonio: Professor Wagner’s:
    “[Stacks: C, C++, and Java Side by
    Side](http://www.cs.utsa.edu/~wagner/CS2213/stack/stack.html)”
    (HTML)  
        
     Instructions: This reading covers subunits 2.2.1 and 2.2.2.  
    Please read the information provided in the above link in its
    entirety.  
        
     This reading should take you approximately 30 minutes to
    complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.2.1 Order of Elements Storage in the Array** <span
id="2.2.1"></span> 
*This subunit is covered by the “Stacks: C, C++, and Java Side by Side”
reading listed in subunit 2.2 above.  You should read the article in its
entirety to get a good understanding of how stacks are implemented in C,
C++, and Java programming languages, including the order of elements
stored in an array.  Earlier, we covered the elements of a stack.  Here
we cover the order of elements of a stack when it is built using an
array in programming languages like C++ and Java.*  
  
 This reading should take you approximately 30 minutes to complete.

**2.2.2 Keeping Track of Array Elements** <span id="2.2.2"></span> 
*This subunit is covered by the “Stacks: C, C++, and Java Side by Side”
reading listed in subunit 2.2 above.  You should read the article in its
entirety to get a good understanding of how stacks are implemented in C,
C++, and Java programming languages, including how to track elements
stored in an array.  Earlier, we covered operations such as push and pop
on a stack.  Here we cover how the operations on a stack modify the
stack, but we can still keep track of these elements when the stack is
built using an array in programming languages like C++ and Java.*  
  
 This reading should take you approximately 30 minutes to complete.

**2.3 General Presentation of a Queue** <span id="2.3"></span> 
-   **Reading: Boston University: Robert I. Pitts’s “Queue - Array
    Implementation – Types”**
    Link: Boston University: Robert I. Pitts’s ["Queue - Array
    Implementation -
    Types"](http://www.cs.bu.edu/teaching/c/queue/array/types.html)
    (HTML)  
        
     Instructions: This reading covers append, empty, and serve
    operations on a queue.  It also includes an array-based
    implementation of a queue with constant shuffling.  Please read the
    linked page in its entirety.  
      
     This reading should take you approximately 40 minutes to
    complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: James Madison University: David Bernstein’s “An
    Introduction to Queues with Examples in C++”**
    Link: James Madison University: David Bernstein’s “An introduction
    to Queues with examples in C++: [An Introduction To Queues with
    Examples in
    C++](https://users.cs.jmu.edu/bernstdh/web/common/lectures/slides_cpp_arrayqueue.php)”
    (HTML)  
        
     Instructions: This reading covers subunits 2.3.1 through 2.3.2. 
    When you have accessed the linked page, click on the purple arrow
    (located in the upper left hand side) to move forward.  Around the
    5<sup>th</sup> click, a pop-up message will appear indicating that
    Java will run.  Please be patient; the pop-up will disappear and you
    can read the example code.  Please read the information provided in
    the above link in its entirety.  
        
     This reading should take you approximately 20 minutes to
    complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.3.1 Array Implementation with Periodic Moving** <span
id="2.3.1"></span> 
*This subunit is covered by the “An Introduction to Queues with Examples
in C++” reading listed in subunit 2.3 above.  The first few slides cover
the array implementation with constant shuffling and periodic moving.  A
queue is characterized by fundamental operations such as append, empty,
and serve.  Unlike a stack, in a queue, the addition of entities to the
rear terminal position and removal of entities from the front terminal
position makes it a first-in first-out (FIFO) structure.  This subunit
covers how to implement these queue operations using arrays, and with
the concept of periodic moving.*  
  
 This reading should take you approximately 10 minutes to complete as
broken up below.

**2.3.2 A Circular Array Manipulation** <span id="2.3.2"></span> 
*This subunit is covered by the “An Introduction to Queues with Examples
in C++” reading listed in subunit 2.3 above.  The last two slides cover
the circular array implementation of the queue.  A queue and its
operations can also be implemented as a circular array, which we cover
in this section.  Like in a stack, the elements of a queue can be
constructed using any abstract data type.*  
  
 This reading should take you approximately 15 minutes to complete.


