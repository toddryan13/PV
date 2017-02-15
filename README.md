# Coding Problem

# Preparation

The code you write in completion of this task, as well as your ability to explain the approach you take and the reasoning behind your decisions are extremely important to us.  This is our primary insight into your coding abilities.  _We hope and expect that you will take this aspect of the interview process seriously!_

During the scheduled code review, the developers reviewing your solution with you will be calling on Skype (desired) or Google Hangouts (back up).  During the call, you will be sharing your screen while walking through your solution, so please ensure that you are able to do so using both Skype **and** Google Hangouts.

**Prior to the code review, upload your solution to GitHub and provide Practice Velocity with a link to the shared repository no later than 10 AM the morning after**  **your receipt of this document.**

# Problem Description

Write a program that takes in an event type of either &quot;Register&quot; or &quot;Diagnose&quot; and prints the output specified in the rules below.

# Rules

#### Event type = &quot;Register&quot;

Print the numbers from one to one hundred except in the following cases:

- For multiples of three print &quot;Register&quot; instead of the number
- For the multiples of five print &quot;Patient&quot; instead of the number
- For numbers which are multiples of both three and five print &quot;Register Patient&quot; instead of the number

#### Event type = &quot;Diagnose&quot;

Print the numbers from one to one hundred except in the following cases:

- For multiples of two print &quot;Diagnose&quot; instead of the number
- For the multiples of seven print &quot;Patient&quot; instead of the number
- For numbers which are multiples of both two and seven print &quot;Diagnose Patient&quot; instead of the number

Implement your solution as a Microsoft MVC web application in C# using .NET 4 or newer.
Focus on the following criteria when developing your solution:

- Write your code so that it is easy for one of your peers to add a new event type.
- Use of Object Oriented Principles, such as interfaces and common design patterns
- Submission of a compiling and fully working solution.
- Correct implementation of business rules

# If You Want to Impress

#### Extra Credit Options

If you wish to impress, adding flexibility to your program is an option:

- Use of unit tests (nunit, mstest, or similar framework) is nice.
- Event types could be built into their own DLLs and loaded dynamically from the applications configuration file.
- Anything you can think of to make an interesting and useful design addition to the program, just create a document outlining the design addition and why you chose to implement it and submit it with your program.