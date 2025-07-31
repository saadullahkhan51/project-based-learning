# Project Based Learning

A list of programming tutorials in which learners build an application from scratch. These tutorials are divided into different primary programming languages. Some have intermixed technologies and languages.

To get started, simply fork this repo. Please refer to [CONTRIBUTING.md](CONTRIBUTING.md) for contribution guidelines.

## Table of Contents:

- [C#](#c)
- [C/C++](#cc)
- [Haskell](#haskell)
- [Python](#python)
- [Rust](#rust)
- [Additional resources](#additional-resources)

## C/C++:

- [Build an Interpreter](http://www.craftinginterpreters.com/) (Chapter 14 on is written in C)
- [Write a FUSE Filesystem](https://www.cs.nmsu.edu/~pfeiffer/fuse-tutorial/)
- [Build Your Own Text Editor](http://viewsourcecode.org/snaptoken/kilo/)
- [Build Your Own Lisp](http://www.buildyourownlisp.com/)
- [Implementing a Key-Value Store](http://codecapsule.com/2012/11/07/ikvs-implementing-a-key-value-store-table-of-contents/)
- Writing a minimal x86-64 JIT compiler in C++
  - [Part 1](https://solarianprogrammer.com/2018/01/10/writing-minimal-x86-64-jit-compiler-cpp/)
  - [Part 2](https://solarianprogrammer.com/2018/01/12/writing-minimal-x86-64-jit-compiler-cpp-part-2/)
- [Write a hash table in C](https://github.com/jamesroutley/write-a-hash-table)
- [Let's Build a Simple Database](https://cstack.github.io/db_tutorial/)
- [Linux Container in 500 Lines of Code](https://blog.lizzie.io/linux-containers-in-500-loc.html)
- [Write Your Own Virtual Machine](https://justinmeiners.github.io/lc3-vm/)
- [Learning KVM - Implement Your Own Linux Kernel](https://david942j.blogspot.com/2018/10/note-learning-kvm-implement-your-own.html)
- Write a C compiler
  - [Part 1: Integers, Lexing and Code Generation](https://norasandler.com/2017/11/29/Write-a-Compiler.html)
  - [Part 2: Unary Operators](https://norasandler.com/2017/12/05/Write-a-Compiler-2.html)
  - [Part 3: Binary Operators](https://norasandler.com/2017/12/15/Write-a-Compiler-3.html)
  - [Part 4: Even More Binary Operators](https://norasandler.com/2017/12/28/Write-a-Compiler-4.html)
  - [Part 5: Local Variables](https://norasandler.com/2018/01/08/Write-a-Compiler-5.html)
  - [Part 6: Conditionals](https://norasandler.com/2018/02/25/Write-a-Compiler-6.html)
  - [Part 7: Compound Statements](https://norasandler.com/2018/03/14/Write-a-Compiler-7.html)
  - [Part 8: Loops](https://norasandler.com/2018/04/10/Write-a-Compiler-8.html)
  - [Part 9: Functions](https://norasandler.com/2018/06/27/Write-a-Compiler-9.html)
  - [Part 10: Global Variables](https://norasandler.com/2019/02/18/Write-a-Compiler-10.html)
- [Implementing a Language with LLVM](https://llvm.org/docs/tutorial/#kaleidoscope-implementing-a-language-with-llvm)
- [High-Performance Matrix Multiplication](https://gist.github.com/nadavrot/5b35d44e8ba3dd718e595e40184d03f0)
- Writing a Linux Debugger
  - [Part 1: Setup](https://blog.tartanllama.xyz/writing-a-linux-debugger-setup/)
  - [Part 2: Breakpoints](https://blog.tartanllama.xyz/writing-a-linux-debugger-breakpoints/)
  - [Part 3: Registers and memory](https://blog.tartanllama.xyz/writing-a-linux-debugger-registers/)
  - [Part 4: Elves and dwarves](https://blog.tartanllama.xyz/writing-a-linux-debugger-elf-dwarf/)
  - [Part 5: Source and signals](https://blog.tartanllama.xyz/writing-a-linux-debugger-source-signal/)
  - [Part 6: Source-level stepping](https://blog.tartanllama.xyz/writing-a-linux-debugger-dwarf-step/)
  - [Part 7: Source-level breakpoints](https://blog.tartanllama.xyz/writing-a-linux-debugger-source-break/)
  - [Part 8: Stack unwinding](https://blog.tartanllama.xyz/writing-a-linux-debugger-unwinding/)
  - [Part 9: Handling variables](https://blog.tartanllama.xyz/writing-a-linux-debugger-variables/)
  - [Part 10: Advanced topics](https://blog.tartanllama.xyz/writing-a-linux-debugger-advanced-topics/)

### Network programming

- Let's Code a TCP/IP Stack

  - [Part 1: Ethernet & ARP](http://www.saminiir.com/lets-code-tcp-ip-stack-1-ethernet-arp/)
  - [Part 2: IPv4 & ICMPv4](http://www.saminiir.com/lets-code-tcp-ip-stack-2-ipv4-icmpv4/)
  - [Part 3: TCP Basics & Handshake](http://www.saminiir.com/lets-code-tcp-ip-stack-3-tcp-handshake/)
  - [Part 4: TCP Data Flow & Socket API](http://www.saminiir.com/lets-code-tcp-ip-stack-4-tcp-data-flow-socket-api/)
  - [Part 5: TCP Retransmission](http://www.saminiir.com/lets-code-tcp-ip-stack-5-tcp-retransmission/)

- Programming concurrent servers
  - [Part 1 - Introduction](https://eli.thegreenplace.net/2017/concurrent-servers-part-1-introduction/)
  - [Part 2 - Threads](https://eli.thegreenplace.net/2017/concurrent-servers-part-2-threads/)
  - [Part 3 - Event-driven](https://eli.thegreenplace.net/2017/concurrent-servers-part-3-event-driven/)
  - [Part 4 - libuv](https://eli.thegreenplace.net/2017/concurrent-servers-part-4-libuv/)
  - [Part 5 - Redis case study](https://eli.thegreenplace.net/2017/concurrent-servers-part-5-redis-case-study/)
  - [Part 6 - Callbacks, Promises and async/await](https://eli.thegreenplace.net/2018/concurrent-servers-part-6-callbacks-promises-and-asyncawait/)
 
- MQTT Broker from scratch
  - [Part 1 - The protocol](https://codepr.github.io/posts/sol-mqtt-broker)
  - [Part 2 - Networking](https://codepr.github.io/posts/sol-mqtt-broker-p2)
  - [Part 3 - Server](https://codepr.github.io/posts/sol-mqtt-broker-p3)
  - [Part 4 - Data structures](https://codepr.github.io/posts/sol-mqtt-broker-p4)
  - [Part 5 - Topic abstraction](https://codepr.github.io/posts/sol-mqtt-broker-p5)
  - [Part 6 - Handlers](https://codepr.github.io/posts/sol-mqtt-broker-p6)
  - [Bonus - Multithreading](https://codepr.github.io/posts/sol-mqtt-broker-bonus)
 
## Python:

### Miscellaneous:

- [Build a Simple Interpreter](https://ruslanspivak.com/lsbasi-part1/)
- [Build a Simple Blockchain in Python](https://hackernoon.com/learn-blockchains-by-building-one-117428612f46)
- [Write a NoSQL Database in Python](https://jeffknupp.com/blog/2014/09/01/what-is-a-nosql-database-learn-by-writing-one-in-python/)
- [Build a Distributed Streaming System with Python and Kafka](https://scotch.io/tutorials/build-a-distributed-streaming-system-with-apache-kafka-and-python)
- [Writing a basic x86-64 JIT compiler from scratch in stock Python](https://csl.name/post/python-jit/)
- Making a low level (Linux) debugger
  - [Part 1](https://blog.asrpo.com/making_a_low_level_debugger)
  - [Part 2: C](https://blog.asrpo.com/making_a_low_level_debugger_part_2)
- Implementing a Search Engine
  - [Part 1](http://www.ardendertat.com/2011/05/30/how-to-implement-a-search-engine-part-1-create-index/)
  - [Part 2](http://www.ardendertat.com/2011/05/31/how-to-implement-a-search-engine-part-2-query-index/)
  - [Part 3](http://www.ardendertat.com/2011/07/17/how-to-implement-a-search-engine-part-3-ranking-tf-idf/)
- [Write yourself a Git](https://wyag.thb.lt/)

## Haskell:

- [Write You a Haskell - Build a modern functional compiler](http://dev.stephendiehl.com/fun/)
- [Write Yourself a Scheme in 48 hours](https://en.wikibooks.org/wiki/Write_Yourself_a_Scheme_in_48_Hours)
- [Write You A Scheme, Version 2](https://github.com/write-you-a-scheme-v2/scheme)
- [Roll Your Own IRC Bot](https://wiki.haskell.org/Roll_your_own_IRC_bot)
- [Let's Build A Basic Compiler in Haskell](http://alephnullplex.github.io/cradle/)
- [Making Movie Monad](https://lettier.github.io/posts/2016-08-15-making-movie-monad.html)

## Rust:

- A Simple Web App in Rust
  - [Part 1](http://joelmccracken.github.io/entries/a-simple-web-app-in-rust-pt-1/)
  - [Part 2a](http://joelmccracken.github.io/entries/a-simple-web-app-in-rust-pt-2a/)
  - [Part 2b](http://joelmccracken.github.io/entries/a-simple-web-app-in-rust-pt-2b/)
- [Write an OS in pure Rust](https://os.phil-opp.com/)
- [Build a browser engine in Rust](https://limpet.net/mbrubeck/2014/08/08/toy-layout-engine-1.html)
- [Write a Microservice in Rust](http://www.goldsborough.me/rust/web/tutorial/2018/01/20/17-01-11-writing_a_microservice_in_rust/)
- [Learning Rust with Too Many Linked Lists](http://cglab.ca/~abeinges/blah/too-many-lists/book/README.html)
- Rust in Detail: Writing Scalable Chat Service from Scratch
  - [Part 1: Implementing WebSocket. Introduction.](https://nbaksalyar.github.io/2015/07/10/writing-chat-in-rust.html)
  - [Part 2: Sending and Receiving Messages](https://nbaksalyar.github.io/2015/11/09/rust-in-detail-2.html)
- [Writing a Rust Roguelike for the Desktop and the Web](https://aimlesslygoingforward.com/blog/2019/02/09/writing-a-rust-roguelike-for-the-desktop-and-the-web/)

## Additional Resources

- [React Redux Links](https://github.com/markerikson/react-redux-links)
- [Full Stack Python](https://www.fullstackpython.com/)
- [Node School](https://nodeschool.io/)
- [ScotchIO](https://scotch.io/)
- [Exercism](http://www.exercism.io/)
- [Egghead.io](http://www.egghead.io/)
- [Michael Herman's Blog](http://mherman.org/)
- [Thinkster.io](http://thinkster.io)
- [C Project Based Tutorials](https://github.com/rby90/Project-Based-Tutorials-in-C)
- [Enlight](https://enlight.nyc/)
- [Hack Club Workshops](https://hackclub.com/workshops/)
