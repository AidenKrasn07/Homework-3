Question 1
What does ADT stand for?
Abstract Data Type

Question 2
In your own words, what is an Abstract Data Type?
An ADT is a framework of what a data type does and what it can do.

Question 3
What is the difference between an ADT and its implementation?
ADT is what the data structure does.
Implementation is how the data structure does it.
Stack ADT should be able to do push, pop, and peek, but implementation shows how these operations are used.

Question 4
Can two programmers create different implementations of the same ADT?
Yes, 2 programmers can create different implementations of the same ADT because the ADT only describes what the data structure should do, but the programmers can used different things to make the data structure work.

Question 5
If one programmer creates a Stack using an array and another creates a Stack using a linked list, are both still Stacks?
Yes both are still stacks because it doesn't matter how its made. As long as both implementations follow the rules of the Stack ADT like LIFO and can still able to use push, pop, peek, and isEmpty, the data structure is a stack.

Question 6
What does LIFO mean?
Last in, First out

Question 7
Why did 55 get removed before 15?
55 was removed before 15 because 55 was the last item put into the stack. Since stack follows LIFO, the last item that is added is the first item that is removed.

Question 8
If the Stack contains:
A
B
C
D
and D was added last, which item should pop() remove first?
D

Question 9
Give one real-world or software example where a Stack could be useful.
A browser's back button is an example of a Stack. Each webpage you visit can be added to a Stack. When you press back, the most recently visited page is removed first, allowing you to return to the previous page.

Question 10
What does FIFO mean?
First in, First Out

Question 11
Why was 15 removed before 55?
15 was removed first because it was entered in the Queue first. Since Queue uses FIFO, the first item that goes into the queue, leaves the queue first as well.

Question 12
If customers enter a line in this order:
Alex
Maria
John
Sarah
who should leave the Queue first?
Alex

Question 13
Give one real-world or software example where a Queue could be useful.
A printer is an example of a Queue because if multiple documents are sent to the printer, the documents will be printed out in the order they were sent. The first one gets printed first and so on.

Scenario 1
A text editor remembers your recent actions.
If you type:
A
B
C
the most recent action should be undone first.
Stack or Queue?
Stack because it follows LIFO and since C was typed out the most recent, C should be undone first.

Scenario 2 — Printer
Three students send documents to a printer.
The first document submitted should normally print first.
Stack or Queue?
Queue because it follows FIFO and since the first document was sent first, it will be the one printed out first.

Scenario 3 — Browser Back Button
You visit:
Google
YouTube
GitHub
Amazon
You click the Back button.
Which page should appear first?
What ADT does this resemble?
Since we are now on Amazon, if we click back, it will show GitHub because it it the most recently visited page. This resembles a stack because it follows LIFO.

Scenario 4 — Customer Service
Customers are waiting to talk to an employee.
The person who arrived first should normally be helped first.
Stack or Queue?
Queue because it follows FIFO, so the first customer is going to be helped first.

Scenario 5 — Plates
You place five plates on top of one another.
Which ADT does this represent?
Stack because if you place 5 plates on top of each other, you will take the top one first and the top one is placed last. This follows the LIFO rule.

Stack
Start with an empty Stack.
push(7)
push(12)
push(18)
pop()
push(22)
peek()
Question 14
What does pop() return?
18

Question 15
What does the final peek() return?
22

Queue
Start with an empty Queue.
enqueue(7)
enqueue(12)
enqueue(18)
dequeue()
enqueue(22)
peek()
Question 16
What does dequeue() return?
7

Question 17
What does the final peek() return?
12

Part 17 — Compare the ADTs
Complete the table.

Feature	              Stack	      Queue
Rule		              LIFO        FIFO
Add operation		      push()      enqueue()
Remove operation		  pop()       dequeue()
View next item		    peek()      peek()
First item removed		Last Item   First Item


Question 18
If you implement a Stack using an array, which part is the ADT?
The part that is ADT is the rule that Stack follows and the operations it could use. So, it follows LIFO and the operations are push(), pop(), peek().

Question 19
Which part is the implementation?
The part that is implementation is the code that is used to manage the ADT and how it uses the Stack like using an array or linked list.

Question 20
If you replace the array with a linked list but keep the same Stack operations, did the ADT change?
No, the ADT didn't change because replacing the array with a linked list only changes the implementation, not the ADT. You can still used the rule of LIFO and stack's operations no matter if you use linked list or array.
