# Python-games: The Day I Asked ChatGPT to Teach Me Python. 

I started this project the day I finished a long morning of studying for my CompTIA Security+ exam. I had been using ChatGPT to help clarify concepts by asking it to "Explain this to me like I am a child." and it was working -- I was actually retaining the information. 

Once I felt studied out, I typed in a new prompt:
*"Can you teach me Python? I am a beginner, want to break into IT and have no money. Can you help me?"* 

That single question kicked off an entire day of learning, troubleshooting and building small Python scripts. This project documents that journey.

# Tools Used
- Python
- Linux
- SSH (There are some screenshots where I had to SSH into my VM from my main machine cause my VM UI wasn't cooperating.)

# Skills Demonstrated
- Writing beginner level Python scripts
- Troubleshooting non-working code
- Understanding and applying core programming concepts
- Documenting learning steps clearly
- Using Linux, VS Code and SSH
- Breaking down problems and iterating on solutions

# Methodology
# Setting Up the Environment

I already had a Linux VM on my Windows machine. I installed Python and VS code, then created a working directory using the command **mkdir python101**. Inside that folder is where I began writing those scripts.

# Early Scripts: Learning the Basics
My first scripts were extremely simple -- printing text, doing basic math and experimenting with input. These helped me understand how Python executes code and how the terminal responds.

<img width="559" height="244" alt="Screenshot 2026-02-22 175733" src="https://github.com/user-attachments/assets/0931267c-7ed7-4bca-9711-adee0332f2c2" />

<img width="1044" height="176" alt="Screenshot 2026-02-22 175812" src="https://github.com/user-attachments/assets/6cc58981-e26e-4539-9169-62e2c6705281" />

<img width="773" height="244" alt="Screenshot 2026-02-22 175926" src="https://github.com/user-attachments/assets/30eff9b1-a6c6-4c60-8d77-d4e6a5263c3e" />

<img width="995" height="169" alt="Screenshot 2026-02-22 180010" src="https://github.com/user-attachments/assets/5a4610b1-d740-4079-a4df-dd23a4b41125" />

# Learning Data Types and Variables
ChatGPT gave me a script about data types. I tried to run it and... nothing happened. That confusion led to a deeper explanation of:
- **Data Types:** The kind of information a variable can hold
- **Variables:** Names you assign to pieces of information.

I learned to think of variables as sticky notes on a desk, and data types at the kind of "box" the information lives in.

# Learning f-strings: The Difference Between Concatenation and f-strings

ChatGPT gave me a script that asked for name and age then it was going to print the name and age. The orginal script it gave me had concatenated strings:

<img width="955" height="344" alt="Screenshot 2026-02-23 135317" src="https://github.com/user-attachments/assets/7df23d21-c28e-4573-8d57-c3fa55e9b58d" />

The script didn't work I spent a solid twenty minutes trouble shoooting it until **FINALLY** chat told me about f-strings, formatted strings. I asked chat to explain to me what they are and why they are preferred:
- f-strings let you insert variables directly into strings
- They're cleaner, shorter and more professional
- They support expressions; you can do math inside of them

<img width="981" height="350" alt="Screenshot 2026-02-25 143437" src="https://github.com/user-attachments/assets/b5347b0a-865a-4ac0-ad33-acc2755b9c52" />

And it worked.

<img width="407" height="85" alt="image" src="https://github.com/user-attachments/assets/fd3c6bbc-63d7-485f-99e5-82fb4accc2e7" />

# Doing Math Inside f-strings

Once I learned that f-strings can evaluate expressions, I experimented by building small scripts that calculated values and printed them dynamically. 

<img width="748" height="165" alt="image" src="https://github.com/user-attachments/assets/66391612-432e-4008-9ae4-58e3c9b269a6" />

<img width="463" height="107" alt="image" src="https://github.com/user-attachments/assets/20a20269-bade-4769-9a42-fa68122002dc" />

# Mini-Project: Age Calculator Game

Skills practiced:
- input()
- Using f-strings to display variables
- Converting strings to integers with int()
- Math with variables
- Conditional logic like **if,** **elif,** and **else**

<img width="907" height="565" alt="image" src="https://github.com/user-attachments/assets/f9c987b8-48d7-4868-a92e-b5a18fe7b627" />

<img width="680" height="213" alt="image" src="https://github.com/user-attachments/assets/5d49332d-c5ac-4b9a-b020-f7f6bbd7cb73" />

# Adding Randomness: Lucky Number Generator

What I learned from this one:
- How to use Python libraries with **import random** we use this to generate the *lucky numbers*
- **for** loops looking through the future ages
- Math with variables again. This one isn't new but I'm not great at math so any sort of calculator always makes me happy
- Random numbers with **random.randit()** generates a random number between 1-100
- Conditional give personalized messages

<img width="867" height="636" alt="image" src="https://github.com/user-attachments/assets/5bfc5ca3-490c-4eda-9892-fb18f329ab49" />

<img width="571" height="274" alt="image" src="https://github.com/user-attachments/assets/6bf3b546-a670-4d2e-ab0b-f173b99fcfb0" />

# Conditional Statements

 Before moving forward I needed more clairifaction of **if**, **else**, and **elif**
- if:  Checks whether a condition is True. If it is, Python runs the code inside it
- else: Is the back up plan so if the input for if is false then it will go on to run the next part of the script
- elif: else if: It allows for additonal conditons. Use when you want multiple, mutually exclusive checks, but only one of them should run.

<img width="479" height="189" alt="image" src="https://github.com/user-attachments/assets/893cb232-42a8-47d4-9f26-c595dc4454c1" />

# Modulus Operator

I asked chat to breakdown luckynumbers.py line by line and explain to me what everthing meant. While I was reading through the explaination the words **Modulus Operator (%)** stood out to me. Mostly because I had no clue what it was. i learned:
- Modulus Operator represented in code as this **%** gives you the remainder of a division **remainder = a % b**.

It can be used to do multiple things such as:
- Finding if a number is even or odd
- Getting the last digit ot a number
- Cycle through patterns

I practiced with exercises:
- Even or Odd?
- Last Digit
- Multiple of 5

<img width="469" height="176" alt="image" src="https://github.com/user-attachments/assets/bdf0627a-4bfe-4ab4-999c-70c7fab9c0ab" />

<img width="447" height="119" alt="image" src="https://github.com/user-attachments/assets/7acba0b4-0c9b-4ee8-8a98-df88f6f04027" /> 

<img width="383" height="87" alt="image" src="https://github.com/user-attachments/assets/7f8695c7-54d4-45a8-a2ec-9daabbec3d37" />


2. Last Digit: 

<img width="535" height="123" alt="image" src="https://github.com/user-attachments/assets/aaf7ecbc-d08e-4ce6-a300-cce3573ee074" />

<img width="1276" height="158" alt="image" src="https://github.com/user-attachments/assets/840f624b-5e22-4ea0-a6f6-3b51dd8c13d5" />

3. Multiple of 5?:

<img width="482" height="222" alt="image" src="https://github.com/user-attachments/assets/ff75f135-6987-4e9c-a9cc-7655279a249e" />

<img width="758" height="68" alt="image" src="https://github.com/user-attachments/assets/51160720-baa8-4d9c-af28-e7cd8e67e454" />

<img width="413" height="57" alt="image" src="https://github.com/user-attachments/assets/1c33d9c5-921f-444d-b9aa-179882875a67" />

# Mini-Project: FizzBuzz

With modulus under my belt, I tackled the classic FizzBuzz challenege.
Rules:
- Divisible by 3 --> print "Fizz"
- Divisible by 5 --> print "Buzz"
- Divisible by both --> print "FizzBuzz"
- Otherwise --> print the number

<img width="615" height="292" alt="image" src="https://github.com/user-attachments/assets/a60b5b8a-ff5e-4212-bba0-301ce980e110" />

<img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/1007f2c4-0eae-402f-9269-dbd09cd77729" />

ChatGPT later showed me a shorter, more advanced versions using f-strings.

<img width="675" height="126" alt="image" src="https://github.com/user-attachments/assets/a5a5f9d1-2ede-4f63-a4ea-94d8667af2dd" />

# Final Project: Lucky Number Game 2 

To wrap up the day, ChatGPt helped me build a more advanced lucky number game that combined everything I learned:
- Input
- Loops
- Random numbers
- Conditionals
- f-strings
- Modulus
- Clean formatting

After several iterations and line-by-line explanations, this was the final script I chose

<img width="1018" height="711" alt="image" src="https://github.com/user-attachments/assets/fee60447-7c65-4650-bef6-a26cd1940962" />

<img width="546" height="276" alt="image" src="https://github.com/user-attachments/assets/f3280208-2329-4691-b65f-8019473a4b9b" />

<img width="541" height="313" alt="image" src="https://github.com/user-attachments/assets/094bcb8d-f296-4db6-ace3-514d0cc96734" />

<img width="509" height="87" alt="image" src="https://github.com/user-attachments/assets/8eebc07f-4ca4-4c39-80f7-09e4a302bfaa" />

# Summary

This project was incredibly fun and extremely educational. In a single day, I went from knowing almost nothing(other than my brute force detection script from an earlier project) to writing small functional scripts and understanding core concepts like:
- Variables
- Data Types
- f-strings
- Input/Output
- Conditionals
- Loops
- Random numbers
- Modulus
- Troubleshooting errors
- Reading and understanding code

It also reinforced my ability to document my work and use available tools to learn efficiently.


















 























 





















