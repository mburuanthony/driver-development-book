# driver-development-book


# Intro

This book is on driver development using Rust. You get to procedurally write a UART driver for a RISCV chip called ESP32C3.  

The chip costs less than 8 dollars, kindly... politely...with utmost humility... burn that cash. BURN THAT CAAAASHHH!!! Money machine go BRRRR!!!


This book is currently in active development, chapters will be updated as we go through the [gdsc course](https://gdsc.community.dev/events/details/developer-student-clubs-university-of-nairobi-presents-introduction-to-rust-on-embedded/).  
Here is the [Course outline](./driver_book/src/direction/course_outline.md)  


The class recordings can be found in [this youtube playlist][driver-development-playlist].  


### Why the UART?

The UART driver was chosen because it is simple and hard at the same time. Both a beginner and an experienced folk can learn a lot while writing it.  
For example, the beginner can write a minimal UART and concentrate on understanding the basics of driver development; No-std development,linking, flashing, logging, abstracting things in a standard way, interrupt and error-handling...  
The pseudo_expert on the other hand can write a fully functional concurrent driver while focusing on things like performance optimization,concurrency and parallelism.  

A dev can iteratively work on this one project for a long time while improving on it and still manage to find it challenging on each iteration. You keep on improving.  

Moreover, the UART is needed in almost all embedded devices that require some form of I/O; making it a necessary topic for driver developers.  


The main aim here is to teach, not to create the supreme UART driver ever seen in the multiverse.    

### What this book is NOT
This book does not explain driver development for a particular Operating System or Kernel. Be it Tock, RTOSes, Windows or linux. This book assumes that you are building a generic driver.  


### Quick links

To access the tutorial book, visit : [this link][driver-development-book-website]  
To access the source-code, visit [this repo's sub-folder][driver-code]  
To access the mdbook source files, visit [this-repo/driver_book/src][driver-book-src]  
If you wish to be a contributor, skim through this guide: [book][contribution-book]


## Communication

You can air your thoughts or ask questions at the [dicussion section][discussion-section].  
If you find an issue in the DOCs or CODE, you can raise it [here][issues-section]  



## Notes to the contributors

To intrested contributors, you can go through this very short tiny microscopic brief informative [book][contribution-book].  
The book takes you through the project structure and explains how tasks get suggested & assigned.    
It also helps you troubleshoot any stalled pull-requests by explaining the pull-request requirement-checks.

It is the ["contribution book"][contribution-book]



<!-- hard-link -->
[driver-book-src]: https://github.com/RustaceansKenya/driver-development-book/tree/master/driver_book/src  

<!-- hard-link -->
[discussion-section]: https://github.com/RustaceansKenya/driver-development-book/discussions

<!-- hard-link -->
[issues-section]: https://github.com/RustaceansKenya/driver-development-book/issues

<!-- hard link -->
[contribution-book]: https://rustaceanskenya.github.io/driver-development-book/contribution_book/book/index.html
[driver-development-book-website]: https://rustaceanskenya.github.io/driver-development-book/  
[driver-code]: https://github.com/RustaceansKenya/driver-development-book/tree/master/driver_code  
[driver-development-playlist]: https://www.youtube.com/playlist?list=PL1KAn4vVH-J47SBytmsfVyKYP84pSlfUG
