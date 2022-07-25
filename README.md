# Project based tutorials in C

A list of tutorials that work towards the making of small to large projects in C.

## Table of Contents

- [Project based tutorials in C](#project-based-tutorials-in-c)
  - [Table of Contents](#table-of-contents)
  - [Computer Architecture](#computer-architecture)
  - [Computer Networking](#computer-networking)
  - [Databases](#databases)
  - [Game Development](#game-development)
  - [Operating Systems](#operating-systems)
  - [Programming Languages](#programming-languages)
  - [Uncategorized](#uncategorized)

## Computer Architecture

Name | Description | Link | Tags
-|-|-|-
bitwise |  Bitwise is an educational project where we create the software/hardware stack for a computer from scratch. | [GitHub](https://github.com/pervognsen/bitwise) | `abandoned`, `video`
Emulator 101 | Writing an arcade game emulator is an awesome learning project, and this tutorial will take you through the entire process in a detailed way. Want to really learn how a CPU works? Writing an emulator is the best way to learn about it. | [Link](http://emulator101.com/) | `text`
Virtual Machine in C | Writing a VM in C | [Link](https://felix.engineer/blogs/virtual-machine-in-c/) | `text`, `virtual-machine`
Writing a CHIP-8 emulator | Writing a Chip 8 emulator | <li>[Part 1](http://craigthomas.ca/blog/2014/06/21/writing-a-chip-8-emulator-part-1/)</li><li>[Part 2](http://craigthomas.ca/blog/2014/07/17/writing-a-chip-8-emulator-part-2/)</li><li>[Part 3](http://craigthomas.ca/blog/2015/02/19/writing-a-chip-8-emulator-draw-command-part-3/)</li><li>[Part 4](http://craigthomas.ca/blog/2017/10/15/writing-a-chip-8-emulator-built-in-font-set-part-4/)</li><li>[Part 5](http://craigthomas.ca/blog/2018/09/07/writing-a-chip-8-emulator-instruction-set-part-5/)</li> | `emulator`, `text`
Writing a Game Boy emulator | Writing a Game Boy emulator | [Link](https://cturt.github.io/cinoop.html) | `text`, `emulator`
Write your Own Virtual Machine | In this tutorial, I will teach you how to write your own virtual machine (VM) that can run assembly language programs, such as my friend’s 2048 or my Roguelike. | [Link](https://justinmeiners.github.io/lc3-vm/) | `text`, `virtual-machine`

## Computer Networking

Name | Description | Link | Tags
-|-|-|-
Beej's Guide to Network Programming | Hey! Socket programming got you down? Is this stuff just a little too difficult to figure out from the man pages? You want to do cool Internet programming, but you don’t have time to wade through a gob of structs trying to figure out if you have to call bind() before you connect(), etc., etc. Well, guess what! I’ve already done this nasty business, and I’m dying to share the information with everyone! You’ve come to the right place. This document should give the average competent C programmer the edge s/he needs to get a grip on this networking noise. | [Link](http://beej.us/guide/bgnet/html/multi/index.html)  | `book`
Concurrent Servers | A series of posts about concurrent network servers | <li>[Part 1 - Introduction](https://eli.thegreenplace.net/2017/concurrent-servers-part-1-introduction/) </li><li>[Part 2 - Threads](http://eli.thegreenplace.net/2017/concurrent-servers-part-2-threads/)</li><li>[Part 3 - Event-driven](http://eli.thegreenplace.net/2017/concurrent-servers-part-3-event-driven/)</li><li>[Part 4 - libuv](http://eli.thegreenplace.net/2017/concurrent-servers-part-4-libuv/)</li><li>[Part 5 - Redis case study](http://eli.thegreenplace.net/2017/concurrent-servers-part-5-redis-case-study/)</li><li>[Part 6 - Callbacks, Promises and async/await](http://eli.thegreenplace.net/2018/concurrent-servers-part-6-callbacks-promises-and-asyncawait/)</li> | `text`, `concurrency`, `network-programming`
Building a simple HTTP server | Everything you need to know to Build a simple HTTP server from scratch | [Medium](https://medium.com/from-the-scratch/http-server-what-do-you-need-to-know-to-build-a-simple-http-server-from-scratch-d1ef8945e4fa) | `http`, `text`
Let's code a TCP/IP stack | The purpose of these posts and the resulting software is purely educational - to learn network and system programming at a deeper level. | <li>[Part 1: Ethernet & ARP](http://www.saminiir.com/lets-code-tcp-ip-stack-1-ethernet-arp/)</li><li>[Part 2: IPv4 & ICMPv4](http://www.saminiir.com/lets-code-tcp-ip-stack-2-ipv4-icmpv4/)<li>[Part 3: TCP Basics & Handshake](http://www.saminiir.com/lets-code-tcp-ip-stack-3-tcp-handshake/)</li><li>[Part 4: TCP Data Flow & Socket API](http://www.saminiir.com/lets-code-tcp-ip-stack-4-tcp-data-flow-socket-api/)</li><li>[Part 5: TCP Retransmission](http://www.saminiir.com/lets-code-tcp-ip-stack-5-tcp-retransmission/)</li>| `networking`, `text`
Write an MQTT broker from scratch | It’s been a while that for my daily work I deal with IoT architectures and research best patterns to develop such systems, including diving through standards and protocols like MQTT; as I always been craving for new ideas to learn and refine my programming skills, I thought that going a little deeper on the topic would’ve been cool and useful too. So once again I git init a low-level project on my box pushing myself a little further by sharing my steps. | <li>[Part 1 - The protocol](https://codepr.github.io/posts/sol-mqtt-broker)</li><li>[Part 2 - Networking](https://codepr.github.io/posts/sol-mqtt-broker-p2)</li><li>[Part 3 - Server](https://codepr.github.io/posts/sol-mqtt-broker-p3)</li><li>[Part 4 - Data structures](https://codepr.github.io/posts/sol-mqtt-broker-p4)</li><li>[Part 5 - Topic abstraction](https://codepr.github.io/posts/sol-mqtt-broker-p5)</li><li>[Part 6 - Handlers](https://codepr.github.io/posts/sol-mqtt-broker-p6)</li> | `text`, `mqtt`
Let's make a NTP Client in C | Writing a NTP client in C | [Link](https://lettier.github.io/posts/2016-04-26-lets-make-a-ntp-client-in-c.html) | `ntp`, `text`


## Databases

Name | Description | Link | Tags
-|-|-|-
Let's Build a Simple Database | Writing a sqlite clone from scratch in C | [Link](https://cstack.github.io/db_tutorial/) | `text`, `sqlite`

## Game Development

Name | Description | Link | Tags
-|-|-|-
Astroids Clone | Simple Astroids clone using assets from Kenney's Space Shooter Redux and Space Shooter Extension | [Link](https://gtk.dashgl.com/Astroids/) | `tutorial`
Brickout Clone | Make a Brickout Clone using the GTK+ library | [Link](https://gtk.dashgl.com/Brickout/) | `tutorial`
Chess Engine in C | Write a program/engine that plays Chess | [Link](https://www.youtube.com/playlist?list=PLZ1QII7yudbc-Ky058TEaOstZHVbT-2hg) | `tutorial`
Coding a Sudoku Solver in C | Self explanatory | [Link](https://www.youtube.com/playlist?list=PLkTXsX7igf8edTYU92nU-f5Ntzuf-RKvW) | `tutorial`, `video`
Coding a Rogue/ Nethack in C | Self explanatory | [Link](https://www.youtube.com/playlist?list=PLkTXsX7igf8erbWGYT4iSAhpnJLJ0Nk5G) | `video`, `tutorial`
Create a Game Loop using C and SDL | Learn to create a game loop from scratch using the C programming language and SDL | [Link](https://www.udemy.com/course/game-loop-c-sdl/) | `course`
Creating a 2D platformer | Learn how to create a simple multi-scrolling 2D platformer | [Link](https://www.parallelrealities.co.uk/tutorials/#ppp) | `tutorial`
Creating a 2D shoot 'em up | How to create a simple 2D shoot 'em up | [Link](https://www.parallelrealities.co.uk/tutorials/#shooter) | `tutorial`
Creating a 2D top-down shooter | how to create a simple top-down 2D shooter that we're going to call Battle Arena Donk! Mouse controls will be used extensively throughout | [Link](https://www.parallelrealities.co.uk/tutorials/#bad) | `tutorial`
Handmade Hero | Handmade Hero is an ongoing project by Casey Muratori to create a complete, professional-quality game accompanied by videos that explain every single line of its source code | [Link](https://handmadehero.org/) | `video`, `tutorial`
Hangman | Write hangman the game! | [Link](https://www.youtube.com/playlist?list=PLZ1QII7yudbd2ZHYSEWrSddsvD5PW_r5O) | `video`
How to Program an NES game in C | Self explanatory| [Link](https://nesdoug.com/) | `tutorial`
How to Program a Text Adventure in C | Self explanatory | [Link](https://helderman.github.io/htpataic/htpataic01.html) | `tutorial`
Implementing Solitaire in C | Self explanatory | [Link](https://jborza.github.io/games/2020/07/12/solitaire-cli.html) | `tutorial`
Invaders Clone | Simple Invaders clone using Kenney's Space Shooter redux pack | [Link](https://gtk.dashgl.com/Invaders/) | `tutorial`
Learn How To Develop Your Own GameBoy Games | Self explanatory | [Link](https://www.youtube.com/playlist?list=PLeEj4c2zF7PaFv5MPYhNAkBGrkx4iPGJo)  | `video` 
Learn Video Game Programming in C | Self explanatory | [Link](https://www.youtube.com/playlist?list=PLT6WFYYZE6uLMcPGS3qfpYm7T_gViYMMt) | `video`
Let’s Make: Dangerous Dave | Self explanatory | [Link](https://www.youtube.com/playlist?list=PLSkJey49cOgTSj465v2KbLZ7LMn10bCF9) | `video`
Making a game in C from scratch | Self explanatory | [Link](https://www.youtube.com/playlist?list=PL7Ej6SUky1357r-Lqf_nogZWHssXP-hvH) | `video`
Making a Video Game from Scratch in C | Self explanatory | [Link](https://www.youtube.com/playlist?list=PLlaINRtydtNWuRfd4Ra3KeD6L9FP_tDE7)  | `video`
On Tetris and Reimplementation | Implement Tetris from scratch in C, except the GUI. | [Link](https://brennan.io/2015/06/12/tetris-reimplementation/) | `tutorial`
SDL 2 Isometric Game Tutorial | Code a Isometric Game in C. Isometric video game graphics are graphics employed in video games and pixel art that use a parallel projection, but which angle the viewpoint to reveal facets of the environment that would otherwise not be visible from a top-down perspective or side view, thereby producing a three-dimensional effect. | [Link](https://www.youtube.com/playlist?list=PL6Ikt4l3NbVjb7WR-eTgjOBMNCn7f3u7x) | `video`
Simple Tic Tac Toe in C | Self explanatory | [Link](https://www.youtube.com/playlist?list=PLZ1QII7yudbc7_ZgXA-gIXmME41Rs2GP5) | `video`
Text Adventure | A text based adventure game | <li>[Episode 1](https://youtu.be/J_Igbh0RH8c)</li><li>[Episode 2](https://www.youtube.com/watch?v=7dYKhiruW1M)</li> | `video`
Tic-tac-toe Game in C with SDL | Self explanatory | [Link](https://www.youtube.com/watch?v=gCVMkKgs3uQ) `video` | `sdl`, `tutorial`, `video`
Video Game Physics Tutorial | Learn the physics of video games. Covers various topics. | <li>[Part I: An Introduction to Rigid Body Dynamics](https://www.toptal.com/game/video-game-physics-part-i-an-introduction-to-rigid-body-dynamics)</li><li>[Part II: Collision Detection for Solid Objects](https://www.toptal.com/game/video-game-physics-part-ii-collision-detection-for-solid-objects)</li><li>[Part III: Constrained Rigid Body Simulation](https://www.toptal.com/game/video-game-physics-part-iii-constrained-rigid-body-simulation)</li> | `physics`, `tutorial`
Write Othello Game from scratch in C | Write a crossplatform Othello game - the Othello engine, UI | [Link](https://www.hanshq.net/othello.html) | `tutorial`
Write The Old-School Fire Effect and Bare-Metal Programming in Assembly and C | Draw fire on the screen! | [Link](https://www.hanshq.net/fire.html) | `tutorial`
Writing 2D Games in C using SDL | Self explanatory | [Link](https://www.youtube.com/watch?v=yFLa3ln16w0)  | `video`, `tutorial`
Writing a Game Boy Advance Game | Self explanatory | [Link](https://www.reinterpretcast.com/writing-a-game-boy-advance-game) | `tutorial`

## Operating Systems

Name | Description | Link | Tags
-|-|-|-
Build a minimal multi-tasking OS kernel for ARM from scratch | Self explanatory | [GitHub](https://github.com/jserv/mini-arm-os) | `arm`, `multi-tasking`
Build Your Own Shell | This is the material for a series of workshops I ran at my workplace on how to write a Unix shell. | [GitHub](https://github.com/tokenrove/build-your-own-shell) | `shell`
Building an Operating System for the Raspberry Pi | Self explanatory | [Link](https://jsandler18.github.io/) | `raspberry-pi`
Hacking the Virtual memory | Self explanatory | <li>[Chapter 0: Hack The Virtual Memory: C strings & /proc](https://blog.holbertonschool.com/hack-the-virtual-memory-c-strings-proc/)</li><li>[Chapter 1: Hack The Virtual Memory: Python bytes](https://blog.holbertonschool.com/hack-the-virtual-memory-python-bytes/)</li><li>[Chapter 2: Hack The Virtual Memory: Drawing the VM diagram](https://blog.holbertonschool.com/hack-the-virtual-memory-drawing-the-vm-diagram/)</li><li>[Chapter 3: Hack the Virtual Memory: malloc, the heap & the program break](https://blog.holbertonschool.com/hack-the-virtual-memory-malloc-the-heap-the-program-break/)</li> | `virtual-memory`
 os-tutorial |  How to create an OS from scratch  | [GitHub](https://github.com/cfenollosa/os-tutorial) | `operating-system`
Learning KVM - implement your own kernel  |  Most introduction articles of KVM I found are actually introducing either libvirt or qemu, lack of how to utilize KVM directly, that's why I have this post. | [Link](https://david942j.blogspot.com/2018/10/note-learning-kvm-implement-your-own.html) | `kvm`
 raspberry-pi-os |  Learning operating system development using Linux kernel and Raspberry Pi  | [GitHub](https://github.com/s-matyukevich/raspberry-pi-os) | `raspberry-pi`, `text`
shell-workshop |  Materials from my Strange Loop 2014 workshop, Let's Build a Shell! | [GitHub](https://github.com/kamalmarhubi/shell-workshop) | `shell`, `text`
Malloc tutorial | Let's write a malloc and see how it works with existing programs! | [Link](https://danluu.com/malloc-tutorial/) | `malloc`
Let’s write a Kernel | Self explanatory | <li>[Part 1: Kernel 101](https://arjunsreedharan.org/post/82710718100/kernel-101-lets-write-a-kernel)</li><li>[Part 2: Kernel 201](https://arjunsreedharan.org/post/99370248137/kernel-201-lets-write-a-kernel-with-keyboard)</li> | `kernel`, `text`
Linux containers in 500 lines of code | Self explanatory | [Link](https://blog.lizzie.io/linux-containers-in-500-loc.html) | `containers`, `text`
Operating systems development for Dummies | If you’ve ever used a computer, you may have found yourself wondering how operating systems function on a low level, or even how you you would go about developing one yourself. To say that kernel development is difficult is a severe understatement, it really is “the great pinnacle of programming”. In this guide, we will introduce the basic tools needed and implement a simple operating system in C and x86 Assembly. | [Link](https://medium.com/@lduck11007/operating-systems-development-for-dummies-3d4d786e8ac) | `operating-systems`, `text`
os01 | Bootstrap yourself to write an OS from scratch. A book for self-learner. | [Link](https://tuhdo.github.io/os01/) | `book`
Hack The Kernel | ops-class.org includes everything you need to learn about operating systems online. | [Link](https://www.ops-class.org/) | `course`
Re-Writing BSD 4.4 Shell Commands | Self explanatory | <li>[cat](https://www.youtube.com/watch?v=MCuzvy79WWQ)</li><li>[chmod](https://www.youtube.com/watch?v=p7uJBl4A_BA)</li><li>[echo](https://www.youtube.com/watch?v=69CYF7nJKj8)</li><li>[mkdir](https://www.youtube.com/watch?v=t96qYd4OUBM)</li> | `video`
Writing a Unix Shell | One of the projects that I am exploring at RC, is writing a UNIX shell. This is the first part of a series of posts that will eventually follow. | <li>[Part 1](https://indradhanush.github.io/blog/writing-a-unix-shell-part-1)</li><li>[Part 2](https://indradhanush.github.io/blog/writing-a-unix-shell-part-2)</li><li>[Part 3](https://indradhanush.github.io/blog/writing-a-unix-shell-part-3)</li> | `shell`
Roll your own toy UNIX-clone OS | This set of tutorials aims to take you through programming a simple UNIX-clone operating system for the x86 architecture. The tutorial uses C as the language of choice, with liberally mixed in bits of assembler. The aim is to talk you through the design and implementation decisions in making an operating system. The OS we make is monolithic in design (drivers are loaded through kernel-mode modules as opposed to user-mode programs), as this is simpler. | [Link](http://www.jamesmolloy.co.uk/tutorial_html/) | `unix`, `text`
The little book about OS development | This text is a practical guide to writing your own x86 operating system. It is designed to give enough help with the technical details while at the same time not reveal too much with samples and code excerpts. We’ve tried to collect parts of the vast (and often excellent) expanse of material and tutorials available, on the web and otherwise, and add our own insights into the problems we encountered and struggled with. | [Link](https://littleosbook.github.io/)  | `book`
Write a Shell in C | Self explanatory | [Link](https://brennan.io/2015/01/16/write-a-shell-in-c/) | `shell`
Write a simple memory allocator | This article is about writing a simple memory allocator in C. We will implement malloc(), calloc(), realloc() and free().[Link](https://arjunsreedharan.org/post/148675821737/write-a-simple-memory-allocator) | `allocator`
Write a System Call | Self explanatory |  [Link](https://brennan.io/2016/11/14/kernel-dev-ep3/) | `system-calls`
Write a shell in C | Ever wondered how that terminal just works? A more correct question would be how that shell just works? I had one of those too and It took me a couple of searches and a lot of reading to figure out how. I wrote a shell in C, first a basic and then added few more features on top of it. I’ve written the process for writing a basic shell in C. | [Link](https://danishpraka.sh/2018/01/15/write-a-shell.html) | `shell`


## Programming Languages

Name | Description | Link | Tags
-|-|-|-
acwj | A compiler writing journey | [Link](https://github.com/DoctorWkt/acwj) | `compilers`
Writing a regular expression matcher | Self explanatory | [Link](https://www.cs.princeton.edu/courses/archive/spr09/cos333/beautiful.html) | `regular-expression`
A Regular Expression Matching Can Be Simple And Fast | Self explanatory | [Link](https://swtch.com/~rsc/regexp/regexp1.html) | `regular-expression`
Baby’s First Garbage Collector | Garbage collection is considered one of the more shark-infested waters of programming, but in this post, I’ll give you a nice kiddie pool to paddle around in. (There may still be sharks in it, but at least it will be shallower.) | [Link](http://journal.stuffwithstuff.com/2013/12/08/babys-first-garbage-collector/) | `gc`
 Build Your Own Lisp |  Learn C and build your own programming language in 1000 lines of code! | [Link](http://www.buildyourownlisp.com/) | `book`
Compiler Design in C| Self explanatory | [PDF](https://holub.com/goodies/compiler/compilerDesignInC.pdf) | `book`
Crafting Interpreters | Ever wanted to make your own programming language or wondered how they are designed and built? If so, this book is for you. | [Link](http://www.craftinginterpreters.com/) | `book` 
Let's build a compiler |  A C & x86 version of the "Let's Build a Compiler" by Jack Crenshaw  A C & x86 version of the "Let's Build a Compiler" by Jack Crenshaw  | [Let's Build a Compiler: A C & x86 version](https://github.com/lotabout/Let-s-build-a-compiler) | `compilers`
Write a C Interpreter |  Write a simple interpreter of C. Inspired by c4 and largely based on it.  | <li>[Part 0: Preface](https://github.com/lotabout/write-a-C-interpreter/blob/master/tutorial/en/0-Preface.md)</li><li>[Part 1: Skeleton](https://github.com/lotabout/write-a-C-interpreter/blob/master/tutorial/en/1-Skeleton.md)</li><li>[Part 2: Virtual Machine](https://github.com/lotabout/write-a-C-interpreter/blob/master/tutorial/en/2-Virtual-Machine.md)</li><li>[Part 3: Lexer](https://github.com/lotabout/write-a-C-interpreter/blob/master/tutorial/en/3-Lexer.md)</li><li>[Part 4: Top-down Parsing](https://github.com/lotabout/write-a-C-interpreter/blob/master/tutorial/en/4-Top-down-Parsing.md)</li><li>[Part 5: Variables](https://github.com/lotabout/write-a-C-interpreter/blob/master/tutorial/en/5-Variables.md)</li><li>[Part 6: Functions](https://github.com/lotabout/write-a-C-interpreter/blob/master/tutorial/en/6-Functions.md)</li><li>[Part 7: Statements](https://github.com/lotabout/write-a-C-interpreter/blob/master/tutorial/en/7-Statements.md)</li><li>[Part 8: Expressions](https://github.com/lotabout/write-a-C-interpreter/blob/master/tutorial/en/8-Expressions.md)</li> | `interpreter`
Writing a simple garbage collector in C | Self explanatory | [Link](http://maplant.com/gc.html) | `gc`
Scheme from Scratch | Self explanatory |<li>[Part 1 - Introduction](http://peter.michaux.ca/articles/scheme-from-scratch-introduction)</li><li>[Part 2 - Integers](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_1-integers)</li><li>[Part 3 - Booleans](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_2-booleans)</li><li>[Part 4 - Characters](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_3-characters)</li><li>[Part 5 - Strings](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_4-strings)</li><li>[Part 6 - The Empty List](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_5-the-empty-list)</li><li>[Part 7 - Pairs](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_6-pairs)</li><li>[Part 8 - Symbols](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_7-symbols)</li><li>[Part 9 - Quote](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_8-quote)</li><li>[Part 10 - Environments](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_9-environments)</li><li>[Part 11 - if](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_10-if)</li><li>[Part 12 - Primitive Procedures Part 1](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_11-primitive-procedures-part-1)</li><li>[Part 13 - Primitive Procedures Part 2](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_12-primitive-procedures-part-2)</li><li>[Part 14 - Lambda the Ultimate](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_13-lambda-the-ultimate)</li><li>[Part 15 - Begin](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_14-begin)</li><li>[Part 16 - Cond](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_15-cond)</li><li>[Part 17 - Let](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_16-let)</li><li>[Part 18 - And and Or](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_17-and-and-or)</li><li>[Part 19 - Apply](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_18-apply)</li><li>[Part 20 - Eval](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_19-eval)</li><li>[Part 21 - I/O](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_20-io)</li><li>[Part 22 - Standard Library](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_21-standard-library)</li><li>[Part 23 - Garbage Collection](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_22-garbage-collection)</li><li>[Part 24 - Conclusion](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-conclusion)</li><li>[Part 22 - Standard Library](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_21-standard-library)</li><li>[Part 23 - Garbage Collection](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_22-garbage-collection)</li><li>[Part 24 - Conclusion](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-conclusion)</li> | `scheme`

## Uncategorized

Name | Description | Link | Tags
-|-|-|-
A dummy blockchain implementation in C | Self explanatory | <li>[Part 1](https://myram.xyz/c-blockchain-implementation-1/)</li><li>[Part 2](https://myram.xyz/c-blockchain-implementation-2/)</li> | `blockchain`
 Build Your Own Text Editor  | This is an instruction booklet that shows you how to build a text editor in C. | [Link](https://viewsourcecode.org/snaptoken/kilo/) | `text-editor`
A Bigint Calculator | This is a programming exercise I've wanted to do for a long time: an implementation of arbitrary-precision integer ("bigint") arithmetic in C. | [Link](https://www.hanshq.net/bigint.html) | `calculator`
Zip Files | Write your own ZIP from scratch in C | [Link](https://www.hanshq.net/zip.html) | `compression`
SVG Library in C | In this post I will develop a simple C library to create and save an SVG (Scalable Vector Graphics) file, complete with a few examples of its use. | [Link](http://www.codedrome.com/svg-library-in-c/) | `graphics`
