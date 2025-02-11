---
title: C
layout: default
parent: Programming Languages
nav_order: 2
---

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