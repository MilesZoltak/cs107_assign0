File: readme.txt
Assignment: assign0
Author: Miles Zoltak
Preferred Gender Pronouns: He/Him/His
----------------------

0. Tell us about yourself!  What do you do for fun?  Tell a quick anecdote about something that you feel makes you unique; a talent, experience, anything.
I'm a sophomore and I intent to major in Symbolic Systems, although I don't know my concentration yet.  I'm on the t therteam, running is probably the activity I'm most passionate about.
This text editor is behaving extremely strangely and I don't want to do this anymore so I'm gonna skip to the next section.... I ferment my own soda so theres that jeez it;s doing it again what the heck

1. Please initial the items below to confirm your course enrollment.

[mz ] I will attend the CS107 midterm and final as scheduled and I understand no alternate/makeup exams will be offered except for OAE or official athletics accommodations. The midterm is Friday, November 1st, in class (11:30AM-1:20PM), and the final is Friday, December 13th, 8:30AM-11:30AM.  If applicable, I have notified the course staff of any needed accommodations.
[ mz] I have read and understood the CS107 collaboration policy at https://cs107.stanford.edu/collaboration.html. By adding my initials, I affirm my intention to abide by this policy.

INTRUDER DETECTION ACTIVITY
2a) the username of the intruder is mattv.  I figured this out by making a temp copy of users.list
    then I used the tree command with attributes -i and -o to make an identically ~formatted~ list
    so that I could finally use diff to compare the two, it told me mattv was the difference.
    I used -o to export the tree to a different file location and I used -i to get rid of all the
    graphical tree-structure type characters.
2b) The file is .bash_history and I found it using the ls -a feature to find hidden files.  This
    file contains all of the commands executed by the intruder.  I figured that last bit out by
    using the cat command, I don't really know the significance of the commands but it's clear
    that they are commands nonetheless.
2c) Using the sudo command the intruder executed the following commands:
          sudo dmesg
          sudo emacs /etc/passwd
          sudo cp -r /etc /mnt/usb/etc
          sudo su
    I was able to figure this out using the grep command.  I looked up the commands the intuder did
    via the man command and found that the su command elevated the intruder to a "superuser"...
    that seems significant.

