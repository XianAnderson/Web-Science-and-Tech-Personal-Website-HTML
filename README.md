Personal Website Project - Introduction to Web Science
Project Overview
This project is part of the "Introduction to Web Science" course and focuses on creating a personal website using HTML only. The goal is to build a functional, multi-page website that adheres to specific requirements and best practices. This README provides detailed instructions, guidelines, and expectations for completing the assignment successfully.

Be sure to read this document carefully.  It contains detailed instructions.  You are responsible to read and understand all of these instructions.  If you have questions, be sure to ask, either in class, by email, or at office hours.

When you have a job, you will probably be given tasks to perform or contracts to fulfill.  These will most likely have detailed instructions and requirements that must be satisfied 'to the letter'.  Consider this assignment as practice!  In the instructions which follow, you will be asked to include comments with a particular format in your submission, and the format for these comments is clearly specified.  A program will scan your file looking for these comments.  If you do not follow the required format, your comments will not be recognized by the program, and consequently you will not receive credit for the related item.  So please read the directions carefully and follow all of the requirements!

Overview
For this assignment, you will be creating a personal website.  The content is up to you, but I expect it to be tasteful!  Describe yourself and tell us something that interests you.  Perhaps give a recipe you enjoy, a favorite movie or hobby, a book you have read more than once!
Your site should have two or three pages, and these pages should be linked so that a visitor can reach all of the pages on your site.
In the detailed instructions below, a number of HTML elements are listed.  These elements should exist on one or more of your pages.  Some elements will be on all of the pages, but other elements need only appear on one page.
Comments should be included in the HTML files that indicate where each of the required elements appear.  These comments are how I will find where you have used the elements, so be sure to follow the instructions carefully.  Note: If you have the same HTML element in more than one location, you only have to tag one of the locations with a comment.
You will use an on-line HTML validator to verify that your webpages are correct.  Screenshots of the validator report are part of your submission.
To complete the assignment, submit to Canvas your HTML files, any images that are local to your web page (i.e. aren't hosted on-line), and screen shots from the Validator.
Note: For this assignment, do not include any styling or scripting on your site, only HTML.
Getting Started
You can write your webpages using your favorite text editor. 
Create a directory on your computer, then add your HTML files to this directory.
Be sure that your 'main' file is called index.html.
You can view your results by double-clicking one of the html files.  Your computer should start up your web browser, then render your page(s).
When you are done with a page, validate your work using an on-line HTML validator:
    http://validator.w3.org/Links to an external site.
Capture a screenshot of the results, which will be part of your submission.  Save these images as PNG files.
Required Elements
You should have each of the following HTML elements at least one place in at least one of your HTML files:

Title
Header
Footer
Navigation
Section
Heading -- one of <h1>, <h2>, etc
Paragraph
Span
Anchor -- an external link (a link to some webpage on a different website)
Anchor -- an internal link (a link to a different webpage on your website)
List -- either ordered or unordered
Figure
FigureCaption
Image
Table
Details
Summary
Note: Each of the above are the actual HTML tags you must use.  For example, do not simply call something a 'Title', or use the word 'Title' in a heading.  Instead, use a <title>...</title>.

Required Comments
One instance of each of the above HTML tags should be 'marked' with a comment, so my program can find your tag.

Your comments should look like this:

<!-- Requirement-1.Y -->
<element>...</element>
All of the requirements start with 'Requirement-1' (these are all for assignment 1), and the letter suffix (the 'Y' in the example) is the letter in the above list of Required Elements.  So, for example, your HTML for the Title element might be:

<html>
<head>
<!-- Requirement-1.A -->
<title>Welcome to my website</title>
Don't place two or more required elements on the same line of the file, so that each can be preceded by its own comment.
