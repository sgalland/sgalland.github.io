---
title: C
layout: default
parent: Programming Languages
nav_order: 2
---

https://github.com/gurugio/lowlevelprogramming-university

```mermaid
flowchart TD;
    accTitle: the diamond pattern
    accDescr: a graph with four nodes: A points to B and C

    b1[C Programming: A Modern Approach]
    b2[The C Programming Language]
    b3[The Practice of Programming]
    b4[Algorithms in C]
    b5[C Interfaces and Implementation]
    b6[The Standard C Library]

    b9[C: A Reference Manual]

    b21[The C Puzzle Book]
    b22[The C Answer Book]

    subgraph Beginner Books
        b1-->b4-->b5-->b6;
    end

    
    subgraph Style
        b1-.->b3;
    end

    subgraph Reference Books
        b1-.->b2;
        b2-.->b21;
        b2-.->b22;
        b9;
    end
```

| Name                             | Author    | C Standard | Description                                  |
| -------------------------------- | --------- | ---------- | -------------------------------------------- |
| C Programming: A Modern Approach | K.N. King | C89 / C99  | A solid beginner book with lots of examples. |

[Stanford CS107](https://see.stanford.edu/course/cs107)

http://cs.yale.edu/home/aspnes/classes/223/notes.html

https://www.coursera.org/specializations/c-programming

## Free Resources

### Books

https://github.com/EbookFoundation/free-programming-books/blob/main/books/free-programming-books-langs.md#c

| Name                                                                                                            | Author                                    | C Standard | Description                                  |
| --------------------------------------------------------------------------------------------------------------- | ----------------------------------------- | ---------- | -------------------------------------------- |
| [The C Book](https://publications.gbdirect.co.uk/c_book/)                                                       | Mike Banahan, Declan Brady and Mark Doran | C89        | A solid beginner book with lots of examples. |
| [C Elements of Style](http://www.oualline.com/books.free/style/index.html)                                      | Steve Oualline                            |            |                                              |
| [Modern C](https://gustedt.gitlabpages.inria.fr/modern-c/)                                                      | Jens Gusted                               | C23        |                                              |
| [Algorithm Design (in C)](https://www.ime.usp.br/~pf/algorithms/)                                               | Paulo Feofiloff                           |            |                                              |
| [Beejs Guide to C Programming](http://beej.us/guide/bgc/)                                                       | Brian Jorgansen                           |            |                                              |
| [Dive into Systems](https://diveintosystems.org/book/)                                                          |                                           |            |                                              |
| [Build Your Own Lisp](http://buildyourownlisp.com/)                                                             |                                           |            |                                              |
| [C Programming Notes](https://www.eskimo.com/~scs/cclass/notes/top.html)                                        | Steve Summit                              |            |                                              |
| [The GNU C Programming Tutorial](https://www.it.uc3m.es/pbasanta/asng/course_notes/ctut.pdf)                    | Mark Burgess                              |            |                                              |
| [Learning GNU C](https://www.nongnu.org/c-prog-book/online/index.html)                                          |                                           |            |                                              |
| [Programming in C UNIX System Calls and Subroutines using C](https://users.cs.cf.ac.uk/Dave.Marshall/C/CE.html) | A.D. Marshall                             |            |                                              |
| [Essential C](http://cslibrary.stanford.edu/101/)                                                               | Nick Parlante                             |            |                                              |

### Programming Tutorials

| Name                                                                                                            | Author | C Standard | Description |
| --------------------------------------------------------------------------------------------------------------- | ------ | ---------- | ----------- |
| [Jacob Sorber](https://www.youtube.com/c/JacobSorber)                                                           |        |            |             |
| [Introduction to Programming using C](https://www.youtube.com/playlist?list=PLcb47MKbeHkcBhhAdLDJObMibJsfb8cz4) |        |            |
| [Bro Code C Tutorial](https://www.youtube.com/playlist?list=PLZPZq0r_RZOOzY_vR4zJM32SqsSInGMwe)                 |        |            |             |

https://ocw.mit.edu/courses/6-087-practical-programming-in-c-january-iap-2010/resources/mit6_087iap10_lec01/

http://doctord.dyndns.org/Courses/UNH/CS610/Phil's_C_Course.htm

https://c-faq.com/







https://blog.llvm.org/2011/05/what-every-c-programmer-should-know_14

https://www.intel.com/content/www/us/en/developer/tools/documentation.html


