#  Project title : Command-Line Typing Speed Tester
#  Overview of the Project:
This is a simple command-line application created to help the user improve in both typing speed and accuracy. 
It chooses motivational quotes randomly from a pre-defined list of quotes and asks the user to type out the phrase with maximum speed and accuracy. Then, it computes and displays WPM and a percentage accuracy score. 

#  Features
•Paragraph Randomizing: This automatically chooses a different paragraph for every test using the random library.

•Time Tracking: Uses the time library to precisely measure how much time it takes for the user to finish the typing task.

WPM Calculation: Calculates the typing speed, in words per minute, dependent upon the number of words typed and the time elapsed.

•Accuracy Score: This returns the accuracy in percentage form. Note that currently, it is a simple set-based comparison, checking if words exist in the target 
text, which, while useful as a rough demonstration, has fairly serious limitations.

• Replay Functionality: Allows the user to start a new test easily without restarting the script.
 
# Technologies/Tools Used
Technology\tPurpose
1. Python 3: The main programming language used for implementation.
 
2.Time module	Used to measure elapsed time for speed calculation.

3 Random module Used for selecting random paragraphs for the test.

4.Command Line Interface (CLI)\tThe interface through which the interactions with the application are made.

# Steps to Install & Run the Project
1.Installation is minimal since this project is a single-file Python script and uses only standard libraries.

# Prerequisites
1.Python 3 must be installed on your system.

# Running the Script
1. Save the Code: Save the given code into a file called typing_test.py.
2.	Open Terminal: Open your terminal or command prompt and head to the directory where you've saved the file.
3. Execute: Run the script using the Python interpreter:
Bash
python typing_test.py
 
Instructions for Testing
1. Begin Test: Run the script based on the "Steps to Install & Run" section.
2.	Wait for Prompt: The script will display an ornamental border and the following instructions5.
3.	Type the Text: The source paragraph will appear. Start typing the paragraph immediately.
o	IMPORTANT: Time will be measured from the time the source text is printed.
4.	Submit: After you are done typing the phrase, hit Enter.
5. Review Results: The script will output your results including: Total words, Time used, Accuracy and Speed (WPM)6.
6.	Again: Type yes if you want to try again, anything else to quit (such as no or just press Enter).


# Problem Statement 
1.While typing speed and accuracy remain critical elements in the modern digital workplace, few users are aware of their current metrics or possess easily accessible tools to practice and track their progress. The problem is to provide a simple, immediate, and accessible tool for users to measure their typing speed in Words Per Minute and their accuracy within a command-line environment, motivating continuous improvement. 

# Overview of the Project 
1.The project, Command-Line Typing Speed Tester, is scoped to deliver the core functionality 
of a typing test within a terminal interface. 
# Inclusions: 
• Random selection and display of a motivational text prompt. 
• Accurate timing of the duration of the user input. 
• Calculation and display of Words Per Minute (WPM) and basic accuracy. 
• Ability to retry the test. 
# Exclusions: 
• A Graphical User Interface (GUI). 
• User authentication or maintaining profiles, or saving performance history data. 
• Advanced accuracy metrics, such as character-level error tracking and complex error 
handling. 
• Online leaderboards or networking capabilities. 

# Target Users 
The following are the target users of this project: 
• Students/Developers: Those who use the command line very often and want a fast, 
distraction-free solution to practice typing. 
• Beginner Programmers: Users whose main focus is to understand the basics of 
Python, such as time measurement, manipulation of strings, and basic input/output. 
• Basic skill assessment users: Any user interested in just a simple, straightforward measure 
of their current typing speed. 
High-Level Features 
The system offers three high-level capabilities, aligning with the three major functional 
modules requirement: 
1.  Text Provision & Input Module 
o Function: This program should randomly choose a typing prompt and then handle user 
text input. 
o 
High-Level Feature: Randomly present the user with a source paragraph and capture 
their corresponding input text. 
2. Performance Measurement Module  
o 
o 
recognizes the test time and calculates the rate metrics that 
High-Level Feature: Show an exact timing of the length of the user's typing session 
and calculate a WPM score; 
3.  Result Calculation & Display Module  
Compares the user's input against the source text and displays the final results.

High-Level Feature: Calculate a set-based accuracy percentage and present all 
performance metrics - Time, WPM, Accuracy - to the user in a clear, formatted output. 
 
  


