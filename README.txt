Welcome to my Start Page designed to replicate a CLI like Linux Terminal, MS PowerShell, etc...

** THIS HAS NOT BEEN DESIGNED FOR MOBILE USE *yet* AND IS INTENDED FOR DESKTOP USE. I APPOLOGIZE 4K USERS: THIS WAS DESIGNED ON A 1440 MONITOR **

THE CODE EXPLAINED:

HTML & CSS:
The HTML & CSS is very simple in this. I have a mainContainer div to encompass all the designing (in typing this I realize 
I should have used the built in HTML5 main tag). This container is set to a width of 1000px with all content being centered for aesthetics.

Embedded in the mainContainer is the terminalContainer div. This div is the main design of the page as it has a black 
background to represent the CLI. There is a an empty div terminalResultsContainer embedded in the terminalContainer that
is used in the JS script to respond to the user's input. User input is obtained through a form tag that prompts with an input
tag designed for text. This is styled to also have no design with a black background. 

A footer tag is used to house three unordered lists seperated into columns. These lists house achor tags that redirect to seperate web pages
on new tabs in the browser. However, each tag can also be written into the terminal rather than clicked for a redirect.

JS:
In the JS, I added an event listener that is specifically targeting the form tag in the HTML document. This is where all user
input goes.I then specify the page to focus on input from a user, allowing the user to input right away without having
to click into the form text space. Each input is then parsed through variable and based on the input has a response. 
After hitting enter, the user's text is cleared and new commands can be entered. 

MASTER LIST OF COMMANDS:

Open + (website w/ .com/.io/.org/etc...)
google + (desired search)
youtube + (desired youtube search)
wiki + (desired search)
time
date
w3schools
codeacademy
codepen
stackoverflow
brcc
replit
netflix
hulu
amazon
