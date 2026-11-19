# Programming-Assignment
**Student Name:** Tshiamo Lentle - PROG5121
**IDE:** NetBeans 17

##How to Run
1. Open in NetBeans
2. Right-click Main-java > Run
3. Register and Login in Output window
4. Right-click project > Test for unit tests

## Features 
-Username, password, cellvnumber validation
-Login authentication
-Message sending (max 250 chars)

## Refernces
-Farrell, J., 2022. Java Programming 9th ed. Cengage.
-Oracle, 2024. Java Documentation.[online] Available at: https//docs.oracle.com/en/java/javas/17/[Accessed 17 September 2026]
REFERENCES

NetBeans (2026) NetBeans IDE Documentation. Available at:
https://netbeans.apache.org/front/main/docs/ [Accessed 19 November 2026].

Oracle (2026) Java SE Documentation - String, ArrayList and Scanner.
Available at: https://docs.oracle.com/javase/8/docs/ [Accessed 19 November 2026].

W3Schools (2026) Java ArrayList, Java String length() and Java Hash.
Available at: https://www.w3schools.com/java/ [Accessed 19 November 2026].

Rich Developer Campus (2026) PROG6212 POE Brief - Part 3: Stored
Messages, Search, Delete and Report. Johannesburg: Richfield.
# QuickChatApp - PROG5121 POE Part 2

**Student Name:** [Tshiamo Lentle]  
**Student Number:** [ST10540486]  
**Module:** PROG5121 - Programming 1A  
**Assessment:** POE Part 2

## Project Description
QuickChatApp is a Java console application that allows users to register, login and send QuickChat messages. This project implements Part 2 of the POE which focuses on the Message class functionality.

## Features Implemented - Part 2

### Part 1 (Completed)
- User Registration with validation:
    - Username must contain underscore and <=5 characters
    - Password must meet complexity requirements
    - Cellphone number validation for South African format (+27...)
- User Login with welcome message

### Part 2 (Current)
- **Message Class** with full functionality:
    - `checkMessageID()` - Ensures message ID <= 10 characters
    - `checkRecipientCell()` - Validates recipient cell number format
    - `createMessageHash()` - Creates hash: ID:COUNTER:MESSAGE
    - `SentMessage()` - Handles Send/Disregard/Store options
    - `checkMessageLength()` - Validates message <= 250 characters
    - `printMessages()` - Displays sent messages
    - `returnTotalMessages()` - Returns total messages sent
- Messaging loop for multiple messages

- QUICKCHAT APP - POE PART 3

Project: QuickChatApp
Language: Java (NetBeans)
Student: Chad

DESCRIPTION

QuickChatApp is a login and messaging system.
It has 3 parts:
Part 1: Register and Login
Part 2: Send messages with cellphone validation and message ID
Part 3: Store messages, search, delete, longest message, and report

HOW TO RUN

1. Open NetBeans
2. Open project: Documents > NetBeansProjects > QuickChatApp
3. Run QuickChatApp.java
4. Register first, then Login with the same details

TEST DETAILS

Name:Sam
Surname: Smith
Username: Sam_1
Password: Ph&&sec@ke55!!
Cell: +27867890987

PART 3 MENU - WHAT EACH OPTION DOES

a) Display stored messages
   - Shows all messages with ID, Hash, Recipient, Message

b) Display longest stored message
   - Shows the longest message and who it was sent to

c) Search for message by ID
   - Example: type 3
   - Shows message 3

d) Search for message by recipient
   - Example: type +27831234567
   - Shows all messages sent to that number

e) Delete message by ID
   - Example: type 2
   - Deletes that message and shows success

r) Display report
   - Shows total messages sent
   - Shows all stored messages in a neat report

PRELOADED MESSAGES (ALWAYS THERE WHEN YOU RUN)

1 | Did you get the cake?
2 | Where are you?
3 | How is your homework going?
4 | I am going to study.
5 | The Avengers movie was awesome.

All 5 are sent to +27831234567

POE EVIDENCE PHOTOS TO INCLUDE

1. Menu a - Display stored messages
2. Menu b - Longest message
3. Menu c - Search ID 3
4. Menu d - Search +27831234567
5. Menu r - Report with BUILD SUCCESS

FILES IN PROJECT

Login.java - Register, Login, cellphone check, password check
Message.java - Send message, create Message ID, calculate hash, store message
QuickChatApp.java - Main menu, Part 3 menu a/b/c/d/e/r

END OF README
BUILD SUCCESS = PROJECT WORKS
- Storage of sent messages counter

## Project Structure
