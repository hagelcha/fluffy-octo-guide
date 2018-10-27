# X-Team 003 Project Proposal: Password Keeper 3000

See https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code for tips on using *Markdown* tags to format __.md__ files

## Goal

Work as a team to create a project proposal for your X-team to complete together.
The project does not have to be extremely difficult,
but there must be work to do for each member of your team.
You may reference figures using "See figure 1".  
Be sure to submit corresponding image files, i.e. figure1.png (or figure1.jpg) for each figure.

## Grading: To earn full credit, your team's proposal must include:

* (md) documentation: [this file] describing purpose and use of your program

* Description of a program that has:

  ** a main Java program class in a file named Main.java
  
  ** a custom data structure designed and built by your team
  
  ** comprehensive testing of individual units
  
 Caution: You are not being asked to implement this program, at least not yet. 
 We just want your group to make a proposal or pitch for your program.
 
 Tip: Your custom data structure can be composed of or extensions of data structures that you have learned and used in previous programming assignments.  We're looking for decisions about how to build a high-level data structure that will likely have lower-level components.

## Problem Description

Many web services require a username and password to login, and must have some way to store that data. A common problem is a lack of scaleable, comprehensive implementations to store not only the current database, but also continues to store more and more data as the data size increases, such as if a website grew in users. A program that could solve this would store passwords that can be mapped to the usernames, ensuring that the program knows the correct password per username, and would store many passwords. The end goal is to verify if the username and password combination matches, and to then allow/deny the user based on the output of the program, e.g. if they match or not.

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)

  Password Keeper 3000

2. Output: Describe the output your program will produce.  Include and example format of the output produced.

The output would be true if the password entered by the user matches the one that is in the programs database (hashtable). The output would be false if the password entered by the user does not match the one that is stored in the database.

Example output: 
Please enter your password:
True: This password matches the one that we have on file.
False: This password does not match the one that we have on file.

3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.



4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.



5. Types List: Break your solution idea down into units that you think can be implemented with a single class.



Name each interface or class and briefly describe its function or purpose.


## Edit and Submit this file and any figures referenced by this document.

