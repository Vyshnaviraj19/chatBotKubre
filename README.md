# SimpleBot - Chatbot in Java

**SimpleBot** (Kubre) is a beginner-level chatbot built in Java. It interacts with users by greeting them, guessing their age using basic math, demonstrating counting skills, and testing programming knowledge through a simple quiz. This project is designed to help understand key Java concepts like methods, loops, user input, and control flow.

## Features

- Greets the user and asks for their name.
- Guesses the user's age based on remainders from division by 3, 5, and 7.
- Counts from 0 to any number provided by the user.
- Includes a multiple-choice quiz on programming knowledge.

## How It Works

1. **Greeting**: The bot introduces itself (Kubre) and asks for the user's name.
2. **Age Guessing**: The user provides remainders from dividing their age by 3, 5, and 7, and the bot calculates the exact age.
3. **Counting**: The bot counts from 0 to a user-specified number.
4. **Quiz**: A simple quiz tests the user’s programming knowledge, validating the answer.

## File Structure

- `Main.java`: The only source file, containing the full code for SimpleBot.

## Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/Vyshnaviraj19/chatBotKubre.git
    ```

2. Navigate to the project directory:
    ```bash
    cd chatBotKubre
    ```

3. Compile the program:
    ```bash
    javac Main.java
    ```

4. Run the program:
    ```bash
    java Main
    ```

## Example Interaction

Hello! My name is Kubre. I was created in 2024. Please, remind me your name.

**Vysh**  
What a great name you have, Vysh!

Let me guess your age. Enter remainders of dividing your age by 3, 5, and 7.

**2 1 1**  
Your age is 23; that's a good time to start programming!

Now I will prove to you that I can count to any number you want.

**5**  
0! 1! 2! 3! 4! 5!

Let's test your programming knowledge.  
**Why do we use methods?**

1. To repeat a statement multiple times.  
2. To decompose a program into several small subroutines.  
3. To determine the execution time of a program.  
4. To interrupt the execution of a program.

**2**  
Congratulations, have a nice day!
