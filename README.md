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
- Storage of sent messages counter

## Project Structure
