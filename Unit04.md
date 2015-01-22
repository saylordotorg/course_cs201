**Unit 4: Dynamic Memory Allocation** <span id="4"></span> 
*We will now learn about dynamic memory allocation.  Frequently, we know
neither the size of the data nor the Data Structure when implementing
programs and Data Structures.  By learning about dynamic memory
allocation, students will understand how to request memory during
runtime.  We will also discuss the risks of memory allocation and
de-allocation, learning about memory leaks and dangling pointers, among
other potential drawbacks.  Students will learn how to prevent these
risks by utilizing the full capabilities of the C/C++ language to
increase memory use efficiency.*

**Unit 4 Time Advisory**  
This unit will take you approximately 45 minutes to complete.  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 4.1: 5 minutes  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 4.2: .75 hours  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 4.3: .75 hours  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 4.4: .75 hours  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 4.5: .75 hours  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 4.6: .75 hours  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 4.7: .75 hours

**Unit4 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:
-   Describe the design and implementations of Dynamic Memory
    Allocations.
-   Describe the use and implementations of C/C++ language to use memory
    more efficiently.

-   **Reading: James Madison University: Professor Bernstein’s "Dynamic
    Memory Allocation in C++ - An Introduction"**
    Link: James Madison University: Professor Bernstein’s ["Dynamic
    Memory Allocation in C++ - An
    Introduction"](https://users.cs.jmu.edu/bernstdh/web/common/lectures/slides_cpp_dynamic-memory.php) 
    (HTML)  
        
     Instructions: This reading covers units 4.1 through 4.7.  Please
    read this webpage in its entirety.  This reading provides general
    information about Dynamic Memory Allocation, with examples in C++.  
        
     This reading should take you approximately 45 minutes to
    complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**4.1 Static versus Dynamic Memory Allocation** <span id="4.1"></span> 
*The first two slides of the reading address the differences between
static and dynamic allocations and discuss what a memory heap is, the
need for references, and the new operator.*  
  
 This reading should take you approximately 5 minutes to complete.

**4.2 Pointing to Memory Allocation at Run Time** <span
id="4.2"></span> 
*This subunit is covered by the “Dynamic Memory Allocation in C++ - An
Introduction” reading listed in subunit 4.1 above.  Until now, in all
our programs, we have only had as much memory available as we declared
for our variables, with the size of all of them to be determined in the
source code, before the execution of the program.  But what if we need a
variable amount of memory that can only be determined during runtime,
for example, a case in which we need some user input to determine the
necessary amount of memory space?*  
  
 This reading should take you approximately 45 minutes to complete.

**4.3 Using Memory Allocated at Run Time** <span id="4.3"></span> 
*This subunit is covered by the “Dynamic Memory Allocation in C++ - An
Introduction” reading listed in subunit 4.1 above.  Here we look into
how we use pointers in working with the memory allocated at runtime.*  
  
 This reading should take you approximately 45 minutes complete.

**4.4 Run Time Allocation of Arrays** <span id="4.4"></span> 
*This subunit is covered by the “Dynamic Memory Allocation in C++ - An
Introduction” reading listed in subunit 4.1 above.  In order to request
dynamic memory we use the operator new, which is followed by a data type
specifier and—if a sequence of more than one element is required—the
number of these within brackets [ ].  It returns a pointer to the
beginning of the new block of memory allocated.*  
  
 This reading should take you approximately 45 minutes to complete.

**4.5 Returning Memory to the Heap** <span id="4.5"></span> 
*This subunit is covered by the “Dynamic Memory Allocation in C++ - An
Introduction” reading listed in subunit 4.1 above.  Most applications
request memory from the heap when they are running.  It is possible to
run out of memory (you may even have gotten a message like "Running Low
On Virtual Memory") when running a program.  So, it is important to
return memory to the heap when you no longer need it.*  
  
 This reading should take you approximately 45 minutes to complete.

**4.6 Memory Leaks** <span id="4.6"></span> 
*This subunit is covered by the “Dynamic Memory Allocation in C++ - An
Introduction” reading listed in subunit 4.1 above.  Memory leaks when it
is allocated from the heap using the new operator but not returned to
the heap using the delete operator.*  
  
 This reading should take you approximately 45 minutes to complete.

**4.7 Dynamic Memory Allocation for Objects** <span id="4.7"></span> 
*This subunit is covered by the “Dynamic Memory Allocation in C++ - An
Introduction” reading listed in subunit 4.1 above.  We can dynamically
allocate memory for objects, which the last section of the reading
covers in some detail.*  
  
 This reading should take you approximately 45 minutes to complete.


