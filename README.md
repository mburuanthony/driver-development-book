# driver-development-book


# Intro

This book is on driver development using Rust. You get to procedurally write a UART driver for two chips: 
-  a RISCV chip called ESP32C3.  
-  a riscv virtual qemu board.  


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
