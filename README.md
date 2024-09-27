java cCOMP5216 Mobile Computing 2024 S2 
 School of Computer Science Page 1 of 2 
 
Assignment 1 
Academic Planner App 
 
Total: 5 marks 
 
Due date: 5pm 21st
 August 2024 (Week 04) 
 
Submission requirements: 
1. Submit all project files as one zipped file. 
2. You will demonstrate your app to your tutor during the tutorial 
time. 
 
In this assignment, you will extend the ToDoList app you started in the tutorials 
to create an Academic Planner app. This app should help you organise your 
class schedules, assignment deadlines, exam dates and fee due dates. 
Main View Requirements 
1. List View: 
• Display all your class dates and times, assignments due dates, and exam dates. 
Each item should show the name and due date/time. If the due date has passed, 
display “OVERDUE” instead. [0.5 mark] 
• Each item should include a checkbox to mark it as completed. [0.25 mark] 
• Include an “ADD NEW” button to switch to the “Edit/Add Item View” when clicked. 
[0.25 mark] 
• Implement a long-click event to delete an item. When a user attempts to delete 
an item, a pop-up confirmation message should ask: “Have you already 
completed this item?” If the user clicks “YES”, the item should be deleted from 
both the List View and the local Database. [0.25 mark] 
Edit/Add Item View Requirements 
2. Fields and Controls: 
• A text field to input or edit the item name. [0.25 mark] 
• A spinner to select the type of items from a set: class, exam or assignment. 
Tapping the spinner displays a menu showing all available options for the user to 
select. [0.25 mark] 
• A date/time picker to set or update the class dates, exam dates or assignment 
due dates. [0.5 mark] 
• A “Save” button to add代 写COMP5216、 Java
代做程序编程语言 or update the item in the List View and the local databas. 
When adding a new item, capture the item name, item type and due date/time.  COMP5216 Mobile Computing Assignment 1 
 School of Computer Science Page 2 of 2 
Calculate the remaining time until the planned date/time by subtracting the current 
system date/time from the planned date/time. [0.5 mark] 
• A “Cancel” button next to the “Save” button to close the Activity without saving 
changes. When clicked, a pop-up dialog should ask: “Are you sure you want to 
cancel this edit? Your unsaved changes will be discarded if you click YES”. [0.25 
mark] 
 
Data Persistence Requirements 
3. Data Handling: 
• Load the list of items from the local database every time the app is launched. The 
list should be sorted based on the remaining time for each item (a class, an exam 
or an assignment). [0.25 mark] 
• Display the completed item (with checked checkboxes) at the bottom of the list. 
[0.25 mark] 
• Ensure that the “Save” button in the “Edit/Add Item View” updates the List View 
and the local Database. [0.25 mark] 
Demonstration and Compliance 
4. Demonstration 
• Demonstrate that the app can be built and run successfully on an emulator. This 
version of the should be submitted to Canvas. [0.5 marks] 
• Ensure the code complies with the official Android Java code style guidelines. 
This includes proper indentation, a maximum of 100 characters per line, no trailing 
whitespaces, and no unused imports. [0.25 mark] 
Note 
Marks for the successful implementation of each feature will consider how well you 
demonstrate the feature and answer questions from the assessor about your development 
process. 

         
加QQ：99515681  WX：codinghelp
