# Project based tutorials in C

A list of tutorials that work towards the making of small to large projects in C.

## Table of Contents

* [Computer Architecture](#computer-architecture)
* [Computer Networking](#computer-networking)
* [Databases](#databases)
* [Game Development](#game-development)
* [Operating Systems](#operating-systems)
* [Programming Languages](#programming-languages)
* [Uncategorized](#uncategorized)

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

* [Astroids Clone](https://gtk.dashgl.com/?folder=Astroids)
* [Brickout Clone](https://gtk.dashgl.com/?folder=Brickout)
* [Chess Engine In C](https://www.youtube.com/playlist?list=PLZ1QII7yudbc-Ky058TEaOstZHVbT-2hg) `video`
* [Coding A Sudoku Solver in C](https://www.youtube.com/playlist?list=PLkTXsX7igf8edTYU92nU-f5Ntzuf-RKvW) `video`
* [Coding a Rogue/Nethack RPG in C](https://www.youtube.com/playlist?list=PLkTXsX7igf8erbWGYT4iSAhpnJLJ0Nk5G) `video`
* [Create a Game Loop using C and SDL](https://www.udemy.com/course/game-loop-c-sdl/) `course`
* [Creating a 2D platformer](https://www.parallelrealities.co.uk/tutorials/#ppp)
* [Creating a 2D shoot 'em up](https://www.parallelrealities.co.uk/tutorials/#shooter)
* [Creating a 2D top-down shooter](https://www.parallelrealities.co.uk/tutorials/#bad)
* [Handmade Hero](https://handmadehero.org/) `video` `in-progress`
* [Hangman](https://www.youtube.com/playlist?list=PLZ1QII7yudbd2ZHYSEWrSddsvD5PW_r5O) `video`
* [How to Program an NES game in C](https://nesdoug.com/)
* [How to Program a Text Adventure in C](https://helderman.github.io/htpataic/htpataic01.html) `in-progress`
* [Implementing Solitaire in C](https://jborza.github.io/games/2020/07/12/solitaire-cli.html)
* [Invaders Clone](https://gtk.dashgl.com/?folder=Invaders)
* [Learn How To Develop Your Own GameBoy Games](https://www.youtube.com/playlist?list=PLeEj4c2zF7PaFv5MPYhNAkBGrkx4iPGJo) `video` `in-progress`
* [Learn Video Game Programming in C](https://www.youtube.com/playlist?list=PLT6WFYYZE6uLMcPGS3qfpYm7T_gViYMMt) `video`
* [Let's Make: Dangerous Dave](https://www.youtube.com/playlist?list=PLSkJey49cOgTSj465v2KbLZ7LMn10bCF9) `video`
* [Making a game in C from scratch](https://www.youtube.com/playlist?list=PL7Ej6SUky1357r-Lqf_nogZWHssXP-hvH) `video`
* [Making a Video Game from Scratch in C](https://www.youtube.com/playlist?list=PLlaINRtydtNWuRfd4Ra3KeD6L9FP_tDE7) `video` `in-progress`
* [On Tetris and Reimplementation](https://brennan.io/2015/06/12/tetris-reimplementation/)
* [SDL 2 Isometric Game Tutorial](https://www.youtube.com/playlist?list=PL6Ikt4l3NbVjb7WR-eTgjOBMNCn7f3u7x) `video` `in-progress`
* [Simple Tic Tac Toe in C](https://www.youtube.com/playlist?list=PLZ1QII7yudbc7_ZgXA-gIXmME41Rs2GP5) `video`
* Text Adventure `video` `in-progress`
    * [Episode 1](https://youtu.be/J_Igbh0RH8c)
    * [Episode 2](https://www.youtube.com/watch?v=7dYKhiruW1M)
* [Tic-tac-toe Game in C with SDL](https://www.youtube.com/watch?v=gCVMkKgs3uQ) `video`
* Video Game Physics Tutorial
    * [Part I: An Introduction to Rigid Body Dynamics](https://www.toptal.com/game/video-game-physics-part-i-an-introduction-to-rigid-body-dynamics)
    * [Part II: Collision Detection for Solid Objects](https://www.toptal.com/game/video-game-physics-part-ii-collision-detection-for-solid-objects)
    * [Part III: Constrained Rigid Body Simulation](https://www.toptal.com/game/video-game-physics-part-iii-constrained-rigid-body-simulation)
* [Write Othello Game from scratch in C](https://www.hanshq.net/othello.html)
* [Write The Old-School Fire Effect and Bare-Metal Programming in Assembly and C](https://www.hanshq.net/fire.html)
* [Writing 2D Games in C using SDL](https://www.youtube.com/watch?v=yFLa3ln16w0) `video`
* [Writing a Game Boy Advance Game](https://www.reinterpretcast.com/writing-a-game-boy-advance-game)

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

* [A Compiler Writing Journey](https://github.com/DoctorWkt/acwj)
* [A Regular Expression Matcher](https://www.cs.princeton.edu/courses/archive/spr09/cos333/beautiful.html)
* [A Regular Expression Matching Can Be Simple And Fast](https://swtch.com/~rsc/regexp/regexp1.html)
* [Baby's First Garbage Collector](http://journal.stuffwithstuff.com/2013/12/08/babys-first-garbage-collector/)
* [Build Your Own Lisp](http://www.buildyourownlisp.com/) `book`
* [Compiler Design in C](https://holub.com/goodies/compiler/compilerDesignInC.pdf) `book`
* [Crafting Interpreters](http://www.craftinginterpreters.com/) `book` *Chapters 14-30*
* [Let's Build a Compiler: A C & x86 version](https://github.com/lotabout/Let-s-build-a-compiler)
* Write a C Interpreter
    * [Part 0 - Preface](https://github.com/lotabout/write-a-C-interpreter/blob/master/tutorial/en/0-Preface.md)
    * [Part 1 - Skeleton](https://github.com/lotabout/write-a-C-interpreter/blob/master/tutorial/en/1-Skeleton.md)
    * [Part 2 - Virtual Machine](https://github.com/lotabout/write-a-C-interpreter/blob/master/tutorial/en/2-Virtual-Machine.md)
    * [Part 3 - Lexer](https://github.com/lotabout/write-a-C-interpreter/blob/master/tutorial/en/3-Lexer.md)
    * [Part 4 - Top-down Parsing](https://github.com/lotabout/write-a-C-interpreter/blob/master/tutorial/en/4-Top-down-Parsing.md)
    * [Part 5 - Variables](https://github.com/lotabout/write-a-C-interpreter/blob/master/tutorial/en/5-Variables.md)
    * [Part 6 - Functions](https://github.com/lotabout/write-a-C-interpreter/blob/master/tutorial/en/6-Functions.md)
    * [Part 7 - Statements](https://github.com/lotabout/write-a-C-interpreter/blob/master/tutorial/en/7-Statements.md)
    * [Part 8 - Expressions](https://github.com/lotabout/write-a-C-interpreter/blob/master/tutorial/en/8-Expressions.md)
* [Writing a Simple Garbage Collector in C](http://maplant.com/gc.html)
* Scheme from Scratch
    * [Part 1 - Introduction](http://peter.michaux.ca/articles/scheme-from-scratch-introduction)
    * [Part 2 - Integers](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_1-integers)
    * [Part 3 - Booleans](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_2-booleans)
    * [Part 4 - Characters](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_3-characters)
    * [Part 5 - Strings](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_4-strings)
    * [Part 6 - The Empty List](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_5-the-empty-list)
    * [Part 7 - Pairs](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_6-pairs)
    * [Part 8 - Symbols](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_7-symbols)
    * [Part 9 - Quote](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_8-quote)
    * [Part 10 - Environments](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_9-environments)
    * [Part 11 - if](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_10-if)
    * [Part 12 - Primitive Procedures Part 1](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_11-primitive-procedures-part-1)
    * [Part 13 - Primitive Procedures Part 2](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_12-primitive-procedures-part-2)
    * [Part 14 - Lambda the Ultimate](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_13-lambda-the-ultimate)
    * [Part 15 - Begin](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_14-begin)
    * [Part 16 - Cond](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_15-cond)
    * [Part 17 - Let](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_16-let)
    * [Part 18 - And and Or](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_17-and-and-or)
    * [Part 19 - Apply](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_18-apply)
    * [Part 20 - Eval](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_19-eval)
    * [Part 21 - I/O](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_20-io)
    * [Part 22 - Standard Library](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_21-standard-library)
    * [Part 23 - Garbage Collection](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_22-garbage-collection)
    * [Part 24 - Conclusion](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-conclusion)

## Uncategorized

* A dummy blockchain implementation in C
   * [Part 1](https://myram.xyz/c-blockchain-implementation-1/)
   * [Part 2](https://myram.xyz/c-blockchain-implementation-2/)
* [Build Your Own Text Editor](https://viewsourcecode.org/snaptoken/kilo/)
* [How to Write a Video Player in Less Than 1000 Lines](http://dranger.com/ffmpeg/ffmpeg.html)
* [Learn FFmpeg libav the Hard Way](https://github.com/leandromoreira/ffmpeg-libav-tutorial) `in-progress`
* [Write a hash table in C](https://github.com/jamesroutley/write-a-hash-table)
* [Write BigInt Calculator in C](https://www.hanshq.net/bigint.html)
* [Write Your Own Zip from scratch in C](https://www.hanshq.net/zip.html)
* [Writing an SVG Library](http://www.codedrome.com/svg-library-in-c/)
