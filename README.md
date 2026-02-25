# Python-games

# The Day I Asked ChatGPT to Teach Me Python. 

One day not too long after I graduated school and had spent the morning studying for my CompTIA Security+ exam, I was using ChatGPT to help clairify things, my prompts were along the lines of "Explain this to me like I am a child." It was doing a really good job and I was acutally retaining the information. Once I felt studied out I decided to put this prompt into ChatGPT: 

Can you teach me python i am a beginner and want to break into the IT industry and have no money can you help me?

And oh the adventure it took me on. Now I am goind to take you on the same adventure. 

# Tools
- Python
- Linux
- SSH(you'll notice there are some screenshots where I had to ssh into my VM from my main machine cause my VM wasn't cooperating.)

# Methodology

1. The first thing I did was set up my environment. I already had a VM with Linux set up on my main Windows machine. I downloaded Python onto my VM and also downloaded VS code.
2. Once I was in my terminal I used the commmand mkdir python101
3. I got the directory made and now I was ready to start writing some scripts. I started out with some really simple scripts such as:
<img width="559" height="244" alt="Screenshot 2026-02-22 175733" src="https://github.com/user-attachments/assets/0931267c-7ed7-4bca-9711-adee0332f2c2" />
<img width="1044" height="176" alt="Screenshot 2026-02-22 175812" src="https://github.com/user-attachments/assets/6cc58981-e26e-4539-9169-62e2c6705281" />
<img width="773" height="244" alt="Screenshot 2026-02-22 175926" src="https://github.com/user-attachments/assets/30eff9b1-a6c6-4c60-8d77-d4e6a5263c3e" />
<img width="995" height="169" alt="Screenshot 2026-02-22 180010" src="https://github.com/user-attachments/assets/5a4610b1-d740-4079-a4df-dd23a4b41125" />

These were fun and simple and it helped me begin to understand how Python works.

4. Then ChatGPT gave me a script that was about data types
<img width="482" height="99" alt="Screenshot 2026-02-22 191025" src="https://github.com/user-attachments/assets/ed9ad919-d59c-4533-abfe-b65d9c3a1cb8" />

I wrote this and not realzing that this was just part of a script I tried to run it onlly to have nothing happen. Then when I asked ChatGPT to help me trouble shoot that is when I learned about **Data Types** and **Variables.** Data Types is the information that a variable can hold. If Python were a storage room full of boxes. Some hold words, or True/False flags, a list of things or labeled information. The types tells Python what is inside those boxes and how it should behave. A variable is a a name you give to a piece of information. It's like writing something on a sticky note then sticking it to your desk so you can look at it whenever you need to. 

5. Python then asked if I wanted to learn a script that asks for a name and age then prints it. This was the script it gave me.
<img width="955" height="344" alt="Screenshot 2026-02-23 135317" src="https://github.com/user-attachments/assets/7df23d21-c28e-4573-8d57-c3fa55e9b58d" />

The script didn't work I spent a solid twenty minutes trouble shoooting it until **FINALLY** chat told me about f-strings, formatted strings. I asked chat to explain to me what they are and why they are preferred, an f-string is a way to put variable directly inside a string without having to use **+** or **str()**, they are cleaner and easier to read, shorter and less error prone. They are more professionally and widely used and supports expressions. Well that would have been nice to know twenty minues ago chatGPT. But anyway armed with this new information I re wrote the script. 

<img width="981" height="350" alt="Screenshot 2026-02-25 143437" src="https://github.com/user-attachments/assets/b5347b0a-865a-4ac0-ad33-acc2755b9c52" />

And it worked.

<img width="407" height="85" alt="image" src="https://github.com/user-attachments/assets/fd3c6bbc-63d7-485f-99e5-82fb4accc2e7" />

Another thing I learned about f-strings is that you can also do math inside of the strings, which I thought was interesting so with the information that I had learned so far I created this script. 
<img width="748" height="165" alt="image" src="https://github.com/user-attachments/assets/66391612-432e-4008-9ae4-58e3c9b269a6" />
<img width="463" height="107" alt="image" src="https://github.com/user-attachments/assets/20a20269-bade-4769-9a42-fa68122002dc" />

6. Chat asked me if I wanted a beginner friendly mini project with using everything I just learned and of course my answer was yes. It gave me script for an age calculator game.
<img width="907" height="565" alt="image" src="https://github.com/user-attachments/assets/f9c987b8-48d7-4868-a92e-b5a18fe7b627" />
<img width="680" height="213" alt="image" src="https://github.com/user-attachments/assets/5d49332d-c5ac-4b9a-b020-f7f6bbd7cb73" />

It's a silly little script but it was alot of fun and it helped me practice:
- input() to get data from the user
- Converting strings into interger with int()
- Using f-strings to display variables
- Doing math with variables
- Conditional statements like **if**, **elif**, and **else**

7. ChatGPT asked me if I wanted to step it up a little and when I said yes, it gave a script that does age calculations *and* generates a lucky number.
<img width="867" height="636" alt="image" src="https://github.com/user-attachments/assets/5bfc5ca3-490c-4eda-9892-fb18f329ab49" />
<img width="571" height="274" alt="image" src="https://github.com/user-attachments/assets/6bf3b546-a670-4d2e-ab0b-f173b99fcfb0" />

What I learned from this one:
- How to use Python libraries with **import random** we use this to generate the *lucky numbers*
- **for** loops looking through the future ages
- Math with variables again. This one isn't new but I'm not great at math so any sort of calculator always makes me happy
- Random numbers with **random.randit()** generates a random number between 1-100
- Conditional give personalized messages

8. I asked chatGPT to break this script down line by line because I wanted to understand what and why I just wrote what I wrote. The one thing that I was struggling to grasp was the **modulus operator %** then chat gave me some exercises using modulus operator




 





















