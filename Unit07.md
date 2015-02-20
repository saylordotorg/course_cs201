---
layout: default
title: "CS201: Elementary Data Structures"
course_description: "An introductory survey of the specification and implementation of basic abstract data types and their associated algorithms. Structures discussed include stacks, queues, lists, sorting and selection, searching, graphs, hashing, and performance tradeoffs of different implementations and asymptotic analysis of running time and memory usage."
next: ../Unit08
previous: ../Unit06
---
**Unit 7: Searching and Sorting Algorithms** <span id="7"></span> 
*In this unit, students will learn to apply searching and sorting
algorithms to arrays.  Students will also learn how to conduct
worst-case and best-case analysis for these algorithms, determine their
efficiency, and assign them generalized Big O notations.*

**Unit 7 Time Advisory**  
This unit will take you approximately 35 minutes to complete.  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 7.1: 10 minutes  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 7.2: 5 minutes  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 7.3: 5 minutes  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 7.4: 10 minutes  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 7.5: 5 minutes

**Unit7 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:
-   Describe how to perform case analysis for searching and sorting
    algorithms.
-   Describe the efficiency of sorting and searching algorithms.

**7.1 Searching Arrays** <span id="7.1"></span> 
-   **Web Media: YouTube: XoaX.net’s “Linear and Binary Searching”**
    Link: YouTube: Xoax.net’s [“Linear & Binary
    Searching”](http://www.youtube.com/watch?v=wNVCJj642n4) (YouTube)  
        
     Instructions: This video covers linear and binary search.  In
    linear search, we discuss a worst-case target at the end of the
    array and derive the efficiency of the algorithm.  We also look into
    the efficiency of the binary search algorithm.  Please watch the
    video in its entirety.  You only need to watch the video; you can
    disregard the remainder of the text on the page.  The video provides
    general information about Linear and Binary Search using examples
    from C++.  
      
     This lecture should take you approximately 10 minutes to
    complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**7.2 Bubble Sorts for Arrays** <span id="7.2"></span> 
-   **Web Media: Youtube: XoaX.net’s “Bubble Sort”**
    Link: YouTube: Xoax.net’s [“Bubble
    Sort”](http://www.youtube.com/watch?v=P00xJgWzz2c) (YouTube)  
        
     Instructions: This video covers subunits 7.2.1 and 7.2.2.  Please
    watch the video in its entirety.  You only need to watch the video;
    you can disregard the remainder of the text on the page.  This video
    provides general information about bubble sort with examples in
    C++.  
      
     This lecture should take you approximately 5 minutes to complete.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**7.2.1 The Process and Implementation in C++** <span
id="7.2.1"></span> 
*This subunit is covered in the first half of the video lecture “Bubble
Sort” listed in subunit 7.2 above, where we look into the process
associated with the implementation of the bubble sort algorithm in C++. 
Bubble sort works by repeatedly stepping through the list to be sorted,
comparing each pair of adjacent items, and*
*[swapping](http://en.wikipedia.org/wiki/Swap_(computer_science) "Swap (computer science)") them
if they are in the wrong order.  The algorithm gets its name from the
way smaller elements "bubble" to the top of the list.*  
  
 This part of the lecture should take you approximately 2 minutes to
complete. 

**7.2.2 Efficiency Analysis** <span id="7.2.2"></span> 
*This subunit is covered in the second half of the video lecture “Bubble
Sort” listed in subunit 7.2 above, where we look into the number of
inner and outer iterations, the worst-case running time, and the
associated Big-O notation for the algorithm. *  
  
 This part of the lecture should take you approximately 2 minutes to
complete. 

**7.3 Insertion Sorts for Arrays** <span id="7.3"></span> 
-   **Web Media: YouTube: XoaX.net’s “Insertion Sort”**
    Link: YouTube: Xoax.net’s [“Insertion
    Sort”](http://www.youtube.com/watch?v=c4BRHC7kTaQ) (YouTube)  
        
     Instructions: This video covers subunits 7.3.1 and 7.3.2.  Please
    watch the video in its entirety.  You only need to watch the video;
    you can disregard the remainder of the text on the page.  The web
    site provides general information about insertion sort with examples
    in C++.  
      
     This lecture should take you approximately 5 minutes to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**7.3.1 The Process and the Implementation in C++** <span
id="7.3.1"></span> 
*This subunit is covered in the first half of the video lecture
“Insertion Sort” listed in subunit 7.3 above, where we look into the
process associated with the implementation of the insertion sort
algorithm in C++.  Insertion sort is a simple* [*sorting
algorithm*](http://en.wikipedia.org/wiki/Sorting_algorithm "Sorting algorithm")*,
a* *[comparison
sort](http://en.wikipedia.org/wiki/Comparison_sort "Comparison sort") in
which the* *[sorted
array](http://en.wikipedia.org/wiki/Sorted_array "Sorted array") (or
list) is built one entry at a time.  It is not the most efficient
sorting algorithm, but it has a simple implementation and is quite
efficient for small data sets.*  
  
 This part of the lecture should take you approximately 2 minutes to
complete.

**7.3.2 Efficiency Analysis** <span id="7.3.2"></span> 
*This subunit is covered in the second half of the video lecture
“Insertion Sort” listed in subunit 7.3 above, where we look into the
number iterations, the worst-case running time, and the associated Big-O
notation for the algorithm.*  
  
 This part of the lecture should take you approximately 2 minutes to
complete.

**7.4 Selection Sorts for Arrays** <span id="7.4"></span> 
-   **Reading: Algolist.net’s “Selection Sort”**
    Link: Algolist.net’s “[Selection
    Sort](http://www.algolist.net/Algorithms/Sorting/Selection_sort)”
    (HTML)  
        
     Instructions: This reading covers subunits 7.4.1 and 7.4.2.  Please
    read the linked page in its entirety for information about selection
    sort, using examples in C++.  
      
     This reading should take you approximately 10 minutes to
    complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**7.4.1 The Process and the Implementation in C++** <span
id="7.4.1"></span> 
*This subunit is covered in the first half of the video lecture
“Selection Sort” listed in subunit 7.4 above, where we look into the
process associated with the implementation of the selection sort
algorithm in C++.  Selection sort works by first finding the smallest in
the array and exchanging it with the element in the first position, then
finding the second smallest element and exchanging it with the element
in the second position, and continues in this way until the entire array
is sorted.*  
  
 This part of the lecture should take you approximately 5 minutes to
complete.

**7.4.2 Efficiency Analysis** <span id="7.4.2"></span> 
*This subunit is covered in the second half of the video lecture
“Selection Sort” listed in subunit 7.4 above, where we look into the
number of iterations, the worst-case running time, and the associated
Big-O notation for the algorithm.  Selection sort is not difficult to
analyze compared to other sorting algorithms since none of the loops
depend on the data in the array.  It has*
[*O*](http://en.wikipedia.org/wiki/Big_O_notation "Big O notation")*(n2)
time complexity, making it inefficient on large lists, and generally
performs worse than the similar* [*insertion
sort*](http://en.wikipedia.org/wiki/Insertion_sort "Insertion sort")*. 
Selection sort is noted for its simplicity, and also has performance
advantages over more complicated algorithms in certain situations,
particularly where auxiliary memory is limited.*  
  
 This part of the lecture should take you approximately 5 minutes to
complete.

**7.5 Merge Sorts for Arrays** <span id="7.5"></span> 
-   **Web Media: YouTube: XoaX.net’s: “Merge Sort”**
    Link: YouTube: Xoax.net’s: [“Merge
    Sort”](http://www.youtube.com/watch?v=GCae1WNvnZM) (YouTube)  
        
     Instructions: This video covers subunits 7.5.1 and 7.5.2.  Please
    watch the video in its entirety.  You only need to watch the video;
    you can disregard the remainder of the text on the page.   Please
    read the linked page in its entirety for information on merge sort
    using examples in C++.  
      
     This lecture should take you approximately 5 minutes to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**7.5.1 The Process and the Implementation in C++** <span
id="7.5.1"></span> 
*This subunit is covered in the first half of the video lecture “Merge
Sort” listed in subunit 7.5 above, where we look into the process
associated with the implementation of the merge sort algorithm in C++. 
Merge sort is a divide-and-conquer approach in which you produce a
single sequence of items ordered according to some rule, from two or
more previously ordered or unordered sequences, without changing the
items’ size, structure, or total number.  Although more than one pass
may be required for a complete sort, items are selected during each pass
on the basis of the entire key.*  
  
 This part of the lecture should take you approximately 2 minutes to
complete.

**7.5.2 Efficiency Analysis** <span id="7.5.2"></span> 
*This subunit is covered in the second half of the video lecture “Merge
Sort” listed in subunit 7.5 above, where we look into the number of
inner and outer iterations, the worst-case running time, and the
associated Big-O notation for the algorithm.  Merge sort is an*
[O](http://en.wikipedia.org/wiki/Big_O_notation "Big O notation")*(n log
n)*
[*comparison-based*](http://en.wikipedia.org/wiki/Comparison_sort "Comparison sort")[*sorting
algorithm*](http://en.wikipedia.org/wiki/Sorting_algorithm "Sorting algorithm")*. 
Most implementations produce a* [*stable
sort*](http://en.wikipedia.org/wiki/Sorting_algorithm#Classification "Sorting algorithm")*,
which means that the implementation preserves the input order of equal
elements in the sorted output.*  
  
 This part of the lecture should take you approximately 2 minutes to
complete.


