# CS1
BookLibrary
Book Analyzer (CS I Project)
This is a Python-based program that takes information from Project Gutenberg and input from the user to create a library of books that can be added to or removed from. Other features include analyzing the most common words and outputting that in bar graph form, as well as recording personal review scores for an individual’s stored book data.
Library Management: Add, remove, and update book titles and URLs.
Dynamic Fetching: Uses the requests library to download book content directly from the web.
Text Processing: Cleans raw text by removing punctuation and case sensitivity using Regular Expressions (re).
Advanced Filtering: Filters out common "Stop Words" and words shorter than 3 characters to provide meaningful analysis.
Visual Data: Generates a horizontal bar chart in the console to represent word frequency.
Rating System: Keep track of your personal review scores for every book in your collection.
Concepts Applied
Dictionaries: Storing complex, nested data for books.
Lists & Filtering: Processing word lists and removing noise.
Functions: Modularizing code for reusability.
Loops & Menu Logic: Creating a persistent, user-friendly interface.
File I/O: Reading external stop-word files to enhance analysis.
API Requests: Handling network communication and potential errors.
Created by Thomas Tecchio
Computer Science I student
________________________________________
Extra Credit Notes
New Feature: Implemented a persistent "Review Score" management system (Choice 5) that allows users to update ratings independently of the analysis.

