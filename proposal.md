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
  
  Main.java would be the class that actually gets the username and password input, and converts that into a format that is ready to be hashed and salted to see if the output is correct. The main class will input the the data into the data structure, and will then return a true or false message based upon the results of the comparison in the data structure.
  
  ** a custom data structure designed and built by your team
  
  The custom data structure will be a hash table that salts the password input before hashing, and stores the unique salt values in the hash table for easy of comparison. The salt will be generated uniquely on a per user basis, and applied before converting the password into a hashed value. The salt may be generated based on the time the password was added, or based upon the username paired with the password. The data structure will be scaleable to account for the natural growth in size a username-password database has for websites or services. This will be based on a load factor that, when met, will increase the size of the hash table without losing data.
  
  The data structure will have a method that tests the input and received values, and will return a true or false boolean value to whatever class implements it.
  
  ** comprehensive testing of individual units
  
  In order to comprehensively test the program, we will implement JUnit testing framework, and write tests that effectively provide for all code coverage, as we do not want buggy software being used for something as crucial as user account data storage.
  
 Caution: You are not being asked to implement this program, at least not yet. 
 We just want your group to make a proposal or pitch for your program.
 
 Tip: Your custom data structure can be composed of or extensions of data structures that you have learned and used in previous programming assignments.  We're looking for decisions about how to build a high-level data structure that will likely have lower-level components.

## Problem Description

Many web services require a username and password to login, and must have some way to store that data. A common problem is a lack of scaleable, comprehensive implementations to store not only the current database, but also continues to store more and more data as the data size increases, such as if a website grew in users. A program that could solve this would store passwords that can be mapped to the usernames, ensuring that the program knows the correct password per username, and would store many passwords. The end goal is to verify if the username and password combination matches, and to then allow/deny the user based on the output of the program, e.g. if they match or not.

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)

  Password Keeper 3000

2. Output: Describe the output your program will produce.  Include and example format of the output produced.



3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.



4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.



5. Types List: Break your solution idea down into units that you think can be implemented with a single class.



Name each interface or class and briefly describe its function or purpose.


## Edit and Submit this file and any figures referenced by this document.

