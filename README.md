# date-parser-api

## Overview 

i want to be able to send a txt file to a server from the command line 

the txt file will contain paragraphs that each have a date/time with them
the server will need to parse that file, and publish each paragraphs in that file that contains date/time to an rss feed, 5 minutes before the date/time within each paragraph 


## Server

**i will provide root access to a freshly provisioned Ubuntu server hosted on Digital Ocean**

## Parser

The parser will need to recieve a txt file from a remote computer. Ideally via a command line command.
The terminal that sends the command should reveive a success/fail message

When the txt file is reieved it will look like this. 

link 

Most paragraphs contain a date and time.

For paragraphs that contain date and time,
We want to create a function that publishes the paragraph to a RSS feed 5 minutes before that date time.

there should be command line access to a log where we can see the success/fail status of the parser and scheduler.

that's it! 


## deliverables 

- [ ] command line command for sending txt file 
- [ ] rss feed address 
- [ ] command line log






## *1* Deploy a mailin node.js http on server, recieve email

- [ ] i will provide you root access to a fresh ubuntu server
- [ ] you will install https://www.npmjs.com/package/mailin
- [ ] provide a method to send an email to the server to be parsed







feed https://www.npmjs.com/package/rss


