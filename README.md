# sbcl/Steel Bank Common Lisp

**CREATED**: *Mon 2 Jun 2025 01:02 AM GMT*  
**UPDATED**: *Mon 7 Jul 2026 06:39 AM GMT*  

-----

## Installation  

### Linux Mint  

> sudo apt install sbcl  

...to run REPL/Read Eval Print Loop...  

> sbcl  

...3 ways to exit REPL...  

> (exit)  
> (quit)  
> [CTRL] + [D]  

-----

## Install rlwrap  

When you try to use the cursor to move around the lines...some weird characters might appear.  
It is recommended you install rlwrap...which fixes this problem.

> sudo apt install rlwrap  

...then, you can move your cursor going back and forth along the line without any weird characters appearing, anymore.  
To run REPL this time use...

> rlwrap sbcl  

-----

## Example code  

> (print "Hello, world!") ; output: Hello, world!  

...save as: hw1.lisp  

> (format t "Hello, world!~%")  

...to run it...  

> sbcl --script hw2.lisp  

...save as: hw2.lisp  

-----

## Articles

Wikipedia article...  
- https://en.wikipedia.org/wiki/Steel_Bank_Common_Lisp  

-----

## Links

Main web site...  
- https://www.sbcl.org  
- https://www.sbcl.org/manual/index.html


-----

## YouTube Videos

Introduction to Common Lisp / (Channel: CodeNextDoor)  
- https://www.youtube.com/watch?v=GFtEGETLv0o&t=26s
  
