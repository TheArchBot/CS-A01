# Lecture 0

Unary notation : ( base-1) : **a way to represent numbers using a single symbol, like 1, repeated a number of times. ( imagine counting with hands )**

Binary: (base-2): Basically count with 0 and 1 which represents on and off state of bits 

Some computers do use ternary system which are called balanced ternary computers 

usually near zero voltage indicates bit as zero and around 5 volt indicates 1 in computers

we use binary because we already have good Boolean algebra and its easier to work with as more voltage might cause a lot more mistakes  and that can cause a lot more in accuracies .

when you scale it to millions like our modern computers it gets bad in a while cause accurately controlling  that many voltage range is gonna be a mess and never soo accurate for the millions of operations per second as we do daily

## ASCII

1001000  1001001   0100001

on decimal its 72 73 33

It means Hi!

So wait a second you are saying some random bunch of dudes sat in a committee said look this is how we will represent Letters and symbols with these binary numbers in 1961 , yeah it’s that backdated and we follow that till the date … Okay it makes sense at least . It’s like the scientific conventions . It just makes sure all the computers understand each other . There are others but generally a few are in every computers or else it would have been shitty , just imagine talking to a friend and he said ow look i don't use the convention you use so use another one maybe hundreds of thousands … you are smart enough to understand 

So how does it work then

We assigned the binary 01000001 as the letter A . So this binary represents A and so on … by defining Ascii or Unicode or such standards can use any letter or number or symbol just using these binary bits 

Here is an expanded map of ASCII values:

| 0 | NUL | 16 | DLE | 32 | SP | 48 | 0 | 64 | @ | 80 | P | 96 | ` | 112 | p |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | SOH | 17 | DC1 | 33 | ! | 49 | 1 | 65 | A | 81 | Q | 97 | a | 113 | q |  |
| 2 | STX | 18 | DC2 | 34 | ” | 50 | 2 | 66 | B | 82 | R | 98 | b | 114 | r |  |
| 3 | ETX | 19 | DC3 | 35 | # | 51 | 3 | 67 | C | 83 | S | 99 | c | 115 | s |  |
| 4 | EOT | 20 | DC4 | 36 | $ | 52 | 4 | 68 | D | 84 | T | 100 | d | 116 | t |  |
| 5 | ENQ | 21 | NAK | 37 | % | 53 | 5 | 69 | E | 85 | U | 101 | e | 117 | u |  |
| 6 | ACK | 22 | SYN | 38 | & | 54 | 6 | 70 | F | 86 | V | 102 | f | 118 | v |  |
| 7 | BEL | 23 | ETB | 39 | ’ | 55 | 7 | 71 | G | 87 | W | 103 | g | 119 | w |  |
| 8 | BS | 24 | CAN | 40 | ( | 56 | 8 | 72 | H | 88 | X | 104 | h | 120 | x |  |
| 9 | HT | 25 | EM | 41 | ) | 57 | 9 | 73 | I | 89 | Y | 105 | i | 121 | y |  |
| 10 | LF | 26 | SUB | 42 | * | 58 | : | 74 | J | 90 | Z | 106 | j | 122 | z |  |
| 11 | VT | 27 | ESC | 43 | + | 59 | ; | 75 | K | 91 | [ | 107 | k | 123 | { |  |
| 12 | FF | 28 | FS | 44 | , | 60 | < | 76 | L | 92 | \ | 108 | l | 124 |  |  |
| 13 | CR | 29 | GS | 45 | - | 61 | = | 77 | M | 93 | ] | 109 | m | 125 | } |  |
| 14 | SO | 30 | RS | 46 | . | 62 | > | 78 | N | 94 | ^ | 110 | n | 126 | ~ |  |
| 15 | SI | 31 | US | 47 | / | 63 | ? | 79 | O | 95 | _ | 111 | o | 127 | DEL |  |




## **Unicode**  


The problem of ascii was it only used a byte of information so we could theoretically and practically have 255 characters . With unicode we started using more than 8 like 16 , 24 or 32 
so with 32 bit we can count upto 4 billion and solve the counting values 

Unicode still contains the values already fixed by ascii and also adds more like every language , emoji , font , special characters. 

## **Colors (RGB)**

So we figured out how we will represent the characters and symbols and emojis …
but now how do the computers understand colors ?  

actually the same  
remember that 72 73 33  which previously said HI!  
but when we use a color software the values will represent different values of red green and blue 


![Relative](/Lecture-0/RGB.png)

So those same values will represent this shade of Yellow actually 

![Relative](/Lecture-0/Yellow.png)

# **Algorithms**

Remember, so our target is solving problems 
As programmer's we solve problems , if there's no problem then we make it and then solve that ......   

So why am I talking about solving problems in the algorithms ??


Let's take a demo problem and explain why you need algorithm to solve problem 




I recommend you try this course  
[MIT Algorithms Course](https://youtube.com/playlist?list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp&si=fe6kJHq4VuPsmxEe)  




### **N.B.**
I referenced CS courses By MIT and Harvard courses for this Note.

Tags: [[CS]]