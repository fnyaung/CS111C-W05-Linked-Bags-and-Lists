# CS111C-W05-Linked-Bags-and-Lists
Linked Bags and Lists (Chapters 3 and 14)

LabC.zip:
  EntryWayList.java
  EntryWayListDriver.java
  EntryWayListInterface.java
  
Source Code from Week 05 Lecture.zip:
  BagInterface.java
  LinkedBag.java
  ListExample.java
  ListInterface.java
  LList.java
  Node.java
  Student.java 
  
Homework05Files.zip:
  BagInterface.java
  Homework05Drive.java
  LinkedBag.java
  ListInterface.java
  LList.java
  Node.java
  Extra Credit Folder

Table of Contents: 
  1 Nodes
    1.1 Object References
    1.2 Dynamic Data Structures
    1.3 Object References as Links
    1.4 The Node Class
    1.5 Using the Node Class to Create a Chain
    1.6 Iterating the Chain
    1.7 Referring to the Chain
    1.8 An Important Note About Node References and Assignment
    1.9 Node Practice
    1.10 Node Practice Answers
  2 Linked Implementations
    2.1 Linked Bag
    2.2 LList
    2.3 Arrays vs. Linked Nodes

Youtube Video:
https://www.youtube.com/playlist?list=PL5igFWijWBo14bwdBbJNo9sb-TZz_ezYL

Lecture Notes:
https://docs.google.com/document/d/1rjr6p1YZMspGvgd0VqeY96f3x_3ED81BwMdClTHACR8/edit?usp=sharing

Lab C: List Implementation:

Implement the interface you wrote for Lab B (EntryWayListInterface). As a reminder, EntryWayListInterface allows the user to access to list elements only through the beginning and end of the list.

Your implementation can use either an expandable array or linked nodes- it is your choice. You can decide what instance variables are needed. You must implement every method from the interface. Make sure to account for special conditions such as empty lists and singleton lists. Note: your instance data variable should be either a) an array or b) one or more nodes. It should not be an AList or LList object or an ArrayList object.

You can use your Lab B solution file as the interface if you received 100% on Lab B. If you lost points, please first fix any errors before you use your interface file. You can post questions to the forum about how to fix an error. If you did not yet receive a grade on Lab B, you can use the interface file provided on Insight.

Your implementation must:

compile (10 points)
contain these implemented methods: (72 points)
insertHead
insertTail
deleteHead
deleteTail
display
contains
isEmpty
isFull
Also create a driver program to test your implementation (18 points). The driver program will operate from the client perspective. Your driver program should:

display an empty list
add five entries to the list- some at the head and some at the tail
display the list
remove the first entry
remove the last entry
display the list
test to see if elements are in the list (test one element that is in the list and one that is not)
remove the last three elements in the list
try to remove an element from the empty list
Extra Credit (20 points)

Write a second class to implement EntryWayListInterface. Instead of using an array or linked nodes, use either an AList or LList object as your instance data variable. In this way, you are using an existing data type (AList or LList) to implement a new data type (EntryWayListInterface). Inside the methods of this class, invoke methods on the AList or LList object to accomplish the task.

Note: your methods might look very simple... this does not mean they are wrong! smile

Note: if you run your test program using this class to initialize your EntryWayListInterface object, the program should run exactly the same as it did above.
