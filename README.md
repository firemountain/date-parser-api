# date-parser-to-rss-feed

## Overview 

i want to be able to send a txt file to a server from the command line 

the txt file will contain paragraphs that each have a date/time within them

the server will need to parse that txt file, and publish each paragraphs in that file that contains date/time to an rss feed, 
5 minutes before the date/time within each paragraph 


## Server

**i will provide root access to a freshly provisioned Ubuntu server hosted on Digital Ocean**

## Parser

The parser will need to recieve a txt file from a remote computer. Ideally via a command line command.
The terminal that sends the command should reveive a success/fail message

When the txt file is reieved it will look like this. 

https://github.com/firemountain/date-parser-to-rss/blob/master/sample.txt

Most paragraphs contain a date and time.
(see here https://gyazo.com/b508ecfe67b65d11fab13d835107ff16)


For paragraphs that contain date and time,
We want to create a function that publishes the paragraph to a RSS feed 5 minutes before that date time.

there should be command line access to a log where we can see the success/fail status of the parser and scheduler.

that's it! 


## deliverables 

- [ ] command line command for sending txt file 
- [ ] rss feed address 
- [ ] command line log







