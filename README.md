java cCOMP2010J: Data Structures and Algorithms
Assignment 2: Hash Table
Implementation and Word Search
Efffciency
Dr. Nima Afraz and Abdul Wadud
Deadline: 25th November, 2024
Instructions
• This is an individual assignment.
• Submit your code and report as a single zip ffle through the course
portal.
• Ensure your code is well-documented with comments explaining your
thought process.
• Label each section and question clearly in your submission.
• Late submissions will be penalized (see grading scheme).
Overview
In this assignment, you will build a dictionary system using a hash table to
store and search words. You will explore the efffciency of hash map operations
by working with two datasets: one containing 1,000 words and another with
10,000 words. The assignment consists of three main parts: constructing a
hash table, measuring the performance of word searches, and implementing
a word suggestion system for unmatched searches.
1Part 1: Building the Hash Table and Menu
System (50 Marks)
You are required to:
• Load two datasets, small dataset.csv (1K words) and large dataset.csv
(10K words), into separate hash maps.
• Implement a method to load the datasets and insert words into the
hash maps.
• Create a menu-driven system that allows the user to search for words
or exit the program.
Menu System Requirements
Implement a simple command-line menu that runs in an inffnite loop and
provides the following options:
1. Search for a word in the 1K dataset: The program should prompt
the user to enter a word and search for it in the hash map containing
the 1K dataset. Display the result (word found with count or word not
found), along with the computational time and number of comparisons.
2. Search for a word in the 10K dataset: The program should prompt
the user to enter a word and search for it in the hash map containing
the 10K dataset. Display the result as above.
3. Exit the program: Allow the user to exit the loop and terminate the
program.
Example Code for Menu System:
1 while ( true ) {
2 System . out. println ("\ nMenu :");
3 System . out. println ("1. Search for a word in the 1K
dataset ");
4 System . out. println ("2. Search for a word in the 10K
dataset ");
5 System . out. println ("3. Exit ");
6 System . out. print (" Enter your choice : ");
7 }
Listing 1: Menu System Implementation
2Tasks:
• Task 1.1 (20 Marks): Write a method to insert words into the hash
map, ensuring that duplicate words are counted.
• Task 1.2 (20 Marks): Implement the menu system as described above
to allow for word searches in both datasets.
• Task 1.3 (10 Marks): Implement a function 代 写COMP2010J、c/c++，Python
代做程序编程语言to display the contents
of the hash map, showing each word and its count.
Figure 1: Sample Output for the Word Search Program
Part 2: Searching and Performance Analysis
(40 Marks)
This part focuses on the efffciency of searching words in hash maps of different
sizes.
Tasks:
• Task 2.1 (20 Marks): Implement a method to search for a word in
the hash map and print whether it was found, along with its count.
– Search for ’aaron’ for both small (1K) and large (10K) dataset
and add the results (screenshot/table) in the report.
• Task 2.2 (15 Marks): Measure the computational time for searching
a word in the 1K dataset and the 10K dataset. Display the time taken
for each search.
• Task 2.3 (15 Marks): Implement logic to count the number of comparisons
 made during the search and display this count for each search.
3• For task 2.2 and 2.3, test the system for three given words in the
Table. 1. State computational time taken and comparisons for each
word.
Word 1K Dataset 10K Dataset
CompTime (ns) Comparisons CompTime (ns) Comparisons
beijing
monica
angel
Table 1: Comparison of computational time and number of comparisons for
words in the 1K and 10K datasets.
Performance Comparison
After completing the searches, you are required to:
• Compare the average time taken to search words in the 1K dataset
versus the 10K dataset.
• Analyze the results and write a short explanation of why the hash map
remains efffcient even with a larger dataset, using Big-O notation to
support your ffndings.
Submission Guidelines
Submit a single zipped folder to Brightspace containing:
1. Your code, including all class ffles and any additional documentation.
2. A PDF report (max 5 pages) explaining your implementation, code
structure, algorithms used, and performance analysis.
Name your zip ffle: ucdconnectid p2.zip
Example Naming Convention
If your UCD Connect ID is 12345678, your submission should be named:
12345678 p2.zip.
4How to Export a Project to a Zip File
• In IntelliJ, go to File | Export | Project to Zip File.
• Specify the path and click Save to create the zip file.
Grading Scheme
Correctness (50%)
• The code should perform as described and meet the problem requirements.
Efficiency
(30%)
• The program should demonstrate efficient use of the hash map for
searching.
Presentation (20%)
• The report should be clear, well-structured, and include explanations
of the code and results.
Late Submission Penalties
• Less than 15 minutes late: No penalty.
• 15 minutes to 2 hours late: 25% deduction.
• More than 2 hours late: 50% deduction.
5

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
