# Code Cracker : What is this project?
Code Cracker was a project that I created when I wanted to learn how to make simple programs in Python to automate different things for different use-cases. Although it's probably not the cleanest and most efficient piece of Python, it gets the job done and allowed me to learn a lot.

The purpose of this script is to automatically input codes into code-locks into the game Rust. It would input the most likely codes first and then cycle all the way to the least common. Once a code had been entered, it would not repeat the same code again. In order for it to automatically input the codes, I used a library called Pynput which would emulate keys being pressed and it turned out to be the most useful library for this project.

After the code was cracked you would get statistics such as:
- How many codes it took
- Time taken overall
- Average codes per minute entered

After this was created, I tested it in my own private server and realised how powerful this tool actually is and the potential to get access to any door in a matter of hours. Because if this, I refrained from using it on public servers due to fear of getting banned and it being unfair. 
