---
layout: default
title: "CS201: Elementary Data Structures"
course_description: "An introductory survey of the specification and implementation of basic abstract data types and their associated algorithms. Structures discussed include stacks, queues, lists, sorting and selection, searching, graphs, hashing, and performance tradeoffs of different implementations and asymptotic analysis of running time and memory usage."
next: ../Unit09
previous: ../Unit07
---
**Unit 8: Hash Tables, Graphs, and Trees** <span id="8"></span> 
*This unit will identify various problems that computer scientists
encounter when using array indexes and present Hash Tables as a
solution.  Students will learn about different Hash Tables categories,
identifying their respective performance efficiencies.  The unit will
conclude with an introduction to graphs and special graph types known as
trees and binary trees.  We will learn how to implement these new Data
Structures, discuss operations that accompany them, and identify
different ways of traversing, searching, and sorting them.*

**Unit 8 Time Advisory**  
This unit will take you approximately 4.5 hours to complete.  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 8.1: .5 hours  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 8.2: .5 hours  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 8.3: 1 hour  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 8.4: 1.5 hours  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 8.5: 1 hour

**Unit8 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:
-   Describe the design and implementations of Hash Tables.
-   Describe the use and implementations of graphs.
-   Describe the operations associated with the implementation of
    graphs.

**8.1 Categories of Hash Functions, Linear Probing, and Chaining** <span
id="8.1"></span> 
-   **Lecture: YouTube: University of California–Berkeley: Professor
    Johnathan Shewchuk’s "Lecture 21: Hash Tables”**
    Link: YouTube: University of California–Berkeley: Professor
    Johnathan Shewchuk’s "[Lecture 21: Hash
    Tables](http://www.youtube.com/watch?v=UPo-M8bzRrc)” (YouTube)  
      
     Instructions: This video covers hash table data structure.  The
    first part of the video covers the types of hash functions,
    collisions, and the idea of chaining to deal with collisions.  Hash
    collisions are practically unavoidable when hashing a random subset
    of a large set of possible keys.  For example, if 2,500 keys are
    hashed into a million buckets, even with a perfectly uniform random
    distribution, according to the [birthday
    problem](http://en.wikipedia.org/wiki/Birthday_problem "Birthday problem") there
    is a 95% chance of at least two of the keys being hashed to the same
    slot.  Therefore, most hash table implementations have some
    collision-resolution strategy to handle such events.  Some common
    strategies are described below.  This has led to the ideas of linear
    probing and chaining.  
        
     This part of the lecture should take you approximately 30 minutes
    to complete.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**8.2 The Efficiency and Performance of Hash Tables** <span
id="8.2"></span> 
-   **Lecture: YouTube: University of California–Berkeley: Professor
    Johnathan Shewchuk’s "Lecture 21: Hash Tables”**
    Link: YouTube: University of California–Berkeley: Professor
    Johnathan Shewchuk’s "[Lecture 21: Hash
    Tables](http://www.youtube.com/watch?v=UPo-M8bzRrc)” (YouTube)  
      
     Instructions: This video covers hash table data structure.  This
    subunit is covered in the second half of “Lecture 21: Hash Tables”
    listed in subunit 8.1 above, where we look into efficiency and
    performance issues related to the hash table data structure.  
        
     This part of the lecture should take you approximately 30 minutes
    to complete.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**8.3 Graphs** <span id="8.3"></span> 
-   **Lecture: YouTube: University of California – Berkeley: Professor
    Shewchuck’s “Data Structures: Topic Graphs”**
    Link: YouTube: University of California – Berkeley: Professor
    Shewchuck’s “[Data Structures Topic
    Graphs](http://www.youtube.com/watch?v=ylWAB6CMYiY)” (YouTube)  
        
     Instructions: This lecture covers simple graphs, vertices, edges,
    and links.  It discusses the idea of paths in graphs.  Several graph
    types, including directed and undirected, are discussed.  After
    that, the lecture covers data structures such as the adjacency
    matrix, adjacency list, and hash-table based implementations of
    graphs.  To access the video, click on the above link.     
      
     This part of the lecture should take you approximately 1 hour to
    complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**8.4 Additional Graph Concepts: Walk, Trail, Path, and Circuits** <span
id="8.4"></span> 
-   **Reading: University of Utah, Math Circle: Allen Dickson’s
    “Introduction to Graph Theory”**
    Link: University of Utah, Math Circle: Allen Dickson’s
    “[Introduction to Graph
    Theory](http://www.math.utah.edu/mathcircle/fall06.html)” (HTML)  
      
     Instructions: Please click on the link and read through the first
    two sections of the document to get an understanding of walk, trail,
    path, and circuits associated with graphs.  
      
     This reading should take you approximately 1.5 hours to complete.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**8.5 Binary Search Trees (BST)** <span id="8.5"></span> 
-   **Lecture: University of California – Berkeley: Professor
    Shewchuck’s “Data Structures – Binary Search Trees”**
    Link: University of California – Berkeley: Professor Shewchuck’s
     “[Data Structures – Binary Search
    Trees](http://www.youtube.com/watch?v=V_3BM0ykITM)” (YouTube)  
        
     Instructions: This lecture covers the basics of BSTs, using
    linked-list data structure for BSTs, how to do traversals on BSTs,
    different types of traversals, sorting and searching on BSTs, and
    insertion and removal of items from BSTs.  To access the video,
    click on the above link.  Please watch the video in its entirety.  
        
     This part of the lecture should take you approximately 1 hour to
    complete.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.


