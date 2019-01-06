---
layout: default
---

## Intro

During this course the students became accustomed to the UNIX command line and file system structure.
The course laid the foundations so that the student can 
manage packages
install programs
navigate the file system
understands the principles of the file system
understands different file types and how to interact with them

It should be customary for everyone to take this course to be honest, as it helps understand modern
computing and the principles behind it (how do you connect to a server, how does a system track its own ongoing processes etc.)

## Week 1

The first week was when we opened the terminal for the first time. We learned how to navigate the system,
how to view and modify different files and we learned about binary and human readable files.

## Week 2

During the second week we looked deeper into the structure of the Unix filesystem and how it is built.
We learned about read, write and execute permissions and different protocols for connecting to
remote servers.

## Week 3

Then we spent a week on some basic corpus processing and we learned about pipelines and regular expressions
For example, we could use a command like:

```cat life_of_bee.txt | tr -s '\n\t\r ' '\n' | tr -dc "A-Za-z0-9'\n" |
sort | uniq -c | sort -nr | grep "intellect"```

We learned more about text processing tools like sed and tr and also about how to manipulate text files, sort them in different ways.

## Week 4

Next week we looked into scripting, and how to make a script file from something like the above command.
The theme was also UNIX environment variables and modifying the .bashrc file which were for me
a bit difficult to understand in the context of the course. I watched some videos from youtube and I think I got it but I 
feel like this section could be a bit better integrated. The course is for  complete newbies so
It's weird, should I really  have some preferences for modifying my own bash, really, when I just weeks
ago learned how to navigate in the command line environment...? Also, some of the videos are
_insanely_ long and could really use some editing. No basic, entry level introductory video should be over 15 minutes long, or at least should be broken into smaller parts, but I digress.

## Week 5

After getting a feel for scripting we were introduced to installing and running programs. Nothing
out of the ordinary here. I felt like the quiz questions could use some editing as the different 
anwsers are so similar in structure. Example: 

```

What does it mean to install a program locally on a UNIX system?

 
c: The program gets installed somewhere under your own home directory. 
Your and other users' PATH variables are updated to contain the location of the program.
Therefore, everyone can run it from anywhere without specifying a path to the program. 

d. The program gets installed somewhere under your own home directory.
Your PATH variable is updated to contain the location of the program. 
Therefore, you can run it from anywhere without specifying a path to the program.

```

I mean, when you have 30 ECT:s worth of studies behind you from the last few months, 2 jobs on top of your studies and its late fall,
people like me don't like to close-read quiz anwsers that all look exactly similar  and it leads to frustration. Add this to the fact that some of the 
instructional videos are so long, if you want to find some specific bit of information out of an hourlong video its completely futile. I didn't have time to watch the longer videos multiple times to search for some specific anwsers so I just didn't.

## Week 6 and 7

Lastly, we got a crash course into version control, git and github. Using the given instructions, we
made our own command-line repository where we have all our text processing scripts from
the previous weeks and now also the website you are reading this from.
Very useful and quite straight-forward.

All in all I am happy that the course exists, I've learned so very much by doing all these exercises and this really is a nice first step into unix and its functions. I got quite annoyed at times but this course gave me what I wanted, and that was to be able to get some basic understanding and tools to work in the unix environment.
