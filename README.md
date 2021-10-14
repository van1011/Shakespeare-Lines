# Shakespeare

demo: https://devpost.com/software/we-love-shakespeare

Download pdf of lines for single character in Shakespeare play

Inspiration:
When searching for scripts for my play, I could only find full scripts(not separated by part). As a result, every cast member had to print a full document, which was unenvironmental and made it difficult to find lines for rehearsal. This inspired us to create a program that produces pdfs for specific characters' lines. 

What it does:
Select a Shakespeare play and a character from the play. Download a pdf with only that character's line from the website. 

How it works: 
Found scripts for all Shakespeare plays from http://shakespeare.mit.edu/. Used beautifulsoup to find play names and corresponding URLs, recorded in repl database. 
Used beautifulsoup to find all characters in a given play and find all character lines. Produced pdf document with pyFPDF. Created website with Flask, javascript, html, css, hosted on repl. 

Further notes: 
We chose Shakespeare plays because they were avilable on the MIT website and we wanted to try using Beautifulsoup. Would like to expand this to scanning pdfs so users can upload their own scripts instead of choosing from our select list. 

