Download Link: https://assignmentchef.com/product/solved-big-homework-1
<br>
<strong>Data Structures and Algorithms Stacks &amp; Queues </strong>

<strong> </strong><strong>! Observation: The stacks and queues used will be in headers (.h) and will be generic classes (template). </strong>

<strong>  </strong>

Tasks:

<ol>

 <li>Design a stack for double numbers called <em>AdvancedStack</em>, which, besides <em>push, pop, isEmpty, peek</em> methods, it has methods for returning the minimum element (<em>min</em>) and the maximum element (<em>max</em>), which should operate in O(1) time, meaning you can’t obtain the minimum/maximum by traversing any stack array. Your <em>AdvancedStack</em> should be built using the template class Stack from the course. (2p)</li>

</ol>




<ol start="2">

 <li>Finding the path to the examination room at UPB Admission Exam using the Stack data structure (4p)</li>

</ol>

A building from the UPB campus is represented though a N*M binary matrix of blocks (representing corridors/ stairs, walls and laboratory doors). A student, positioned initially at coordinates (0,0) in the building matrix wants to find the door to his examination room at UPB Admission Exam, which has a numerical code (other than 0 and 1): e.g. 101.  In the building matrix, we can have 3 types of values: lab codes, 0 – means corridors/ stairs, 1 – means walls. The student can go through corridors and stairs till the room where one was assigned for the exam. The student can move in any direction (not diagonally) to any matrix block provided the block is not a dead end (walls and doors different from the one he/she is looking for). The task is to check if any path exists so that the student can reach the examination room and print the path, using the stack data structure. The input will be 3 building matrices and the code of the student’s examination room: the first 2 letters represent the building and the other 3 represent the numerical code inside the building, e.g. CJ101.

Example of building matrix for CJ building:

CJbuilding[4][5] = {

{0, 104, 0, 0, 1},

{0, 0, 0, 1, 0},

{1, 0, 1, 101, 102},

{0, 0, 0, 0, 0}

}

Example of output, when the students searches for CJ101:

Path Found!

The path can be: (0, 0) -&gt; (1, 0) -&gt; (1, 1) -&gt; (2, 1) -&gt; (3, 1) -&gt; (3, 2)  -&gt; (3, 3) -&gt; (2, 3)  3.      The teachers from UPB want to stock all the available rooms in the campus, which can be used as examination rooms for admission. The room are stocked in a priority queue. Implement a template class called PriorityQueue using the AdvancedStack class: the rooms are added to the queue in the classical way, at the end of the queue, but when deleting them, the room which is the closest to the building entrance door is selected.  In order to calculate the distance between a room and the building entrance door, the distance formula between 2 points is used. The building entrance door has coordinates (0,0). The room doors have coordinates equal to the line and the column in the matrix building. (4p)




<strong> </strong>

<strong> </strong>