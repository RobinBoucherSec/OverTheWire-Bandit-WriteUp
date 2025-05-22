# OverTheWire-Bandit-WriteUp

## Description:
Here I will display my journey through the Capture the Flags of the chapter Bandit on [OverTheWire](https://overthewire.org/wargames/bandit/). You will find my mistakes & learnings as well as a visual of how I document what I do. Note that I will be quite precise in my explanations so that this repository can be a plus in my portfolio and at the meme time a learning platform for beginners.

## Bandit Levels:

Click on the level you want to see, or scroll down for the complete walkthrough level-by-level:


[Level 0](#level-0) 

[Level 0 → Level 1](#Level-0-→-Level-1)

[Level 1 → Level 2](#Level-1-→-Level-2)


Level 2 → Level 3
Level 3 → Level 4
Level 4 → Level 5
Level 5 → Level 6
Level 6 → Level 7
Level 7 → Level 8
Level 8 → Level 9
Level 9 → Level 10
Level 10 → Level 11
Level 11 → Level 12
Level 12 → Level 13
Level 13 → Level 14
Level 14 → Level 15
Level 15 → Level 16
Level 16 → Level 17
Level 17 → Level 18
Level 18 → Level 19
Level 19 → Level 20
Level 20 → Level 21
Level 21 → Level 22
Level 22 → Level 23
Level 23 → Level 24
Level 24 → Level 25
Level 25 → Level 26
Level 26 → Level 27
Level 27 → Level 28
Level 28 → Level 29
Level 29 → Level 30
Level 30 → Level 31
Level 31 → Level 32
Level 32 → Level 33
Level 33 → Level 34

## Level 0

Always following the tips on in the OverTheWire web site in Bandit Labs, I start with 
```
ssh bandit0@bandit.labs.overthewire.org -p 2220
```
<details><summary>Command explanation</summary>
  
- The `ssh` is used to initiate a secure shell connection to a remote server. 

- `bandit0` is the username and `@bandit.labs.overthewire.org` is the hostname of the remote server I wnat to connect.
  
- `-p 2220` specify the port on which SSH will use to connect.
  
</details>

![Image](https://github.com/RobinBoucherSec/OverTheWire-Bandit-WriteUp/blob/main/images/bandit0.png)

## Level 0 → Level 1

I do the command `ls` to display the content of the current directory.

Then, I do the command `cat` to display the content of the `readme` file.

![image](https://github.com/RobinBoucherSec/OverTheWire-Bandit-WriteUp/blob/main/images/bandit1.png)

And here I find the flag: ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If

## Level 1 → Level 2

I type `exit` to come back to kali@kali and again `ssh bandit1@bandit.labs.overthewire.org -p 2220` making sure that I log with *bandit1*. For the password I use: ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If

I `ls` and find a file named `-`. Since the `-` is usually use to type an input afterword, it is confusing: I type `cat -` and the terminal get stock there. I press ctrl+c to unlock it.

I need to `cat ./-`. Here the `.` is telling "current directory" and `./` tells the shell that I want the file named "-" to be opened. 

Here is the output:

![image](https://github.com/RobinBoucherSec/OverTheWire-Bandit-WriteUp/blob/main/images/bandit2.png)

This is the flag:
263JGJPfgU6LtdEvgfWU1XP5yac29mFx

Level 2 → Level 3
Level 3 → Level 4
Level 4 → Level 5
Level 5 → Level 6
Level 6 → Level 7
Level 7 → Level 8
Level 8 → Level 9
Level 9 → Level 10
Level 10 → Level 11
Level 11 → Level 12
Level 12 → Level 13
Level 13 → Level 14
Level 14 → Level 15
Level 15 → Level 16
Level 16 → Level 17
Level 17 → Level 18
Level 18 → Level 19
Level 19 → Level 20
Level 20 → Level 21
Level 21 → Level 22
Level 22 → Level 23
Level 23 → Level 24
Level 24 → Level 25
Level 25 → Level 26
Level 26 → Level 27
Level 27 → Level 28
Level 28 → Level 29
Level 29 → Level 30
Level 30 → Level 31
Level 31 → Level 32
Level 32 → Level 33
Level 33 → Level 34
