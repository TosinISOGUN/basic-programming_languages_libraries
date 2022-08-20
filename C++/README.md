# Welcome to C++
<img src="https://www.simplilearn.com/ice9/free_resources_article_thumb/What_is_CPP.jpg" width="" height="" />

## What Is C++?
[`C++`](https://www.simplilearn.com/tutorials/cpp-tutorial/cpp-basics) is one of the most well-known and well-used [programming languages](https://www.simplilearn.com/tutorials/programming-tutorial/first-programming-language) today, used by more than four million programmers worldwide. The language made its debut in 1985 as an iteration of the [C programming language](https://www.simplilearn.com/c-programming-article). It began as an extension of C but evolved into a different language with distinctive characteristics and features.

`C++` is a scalable, object-oriented language, perfect for large, scalable applications thanks to its discrete and direct memory management capabilities and low-level machine functions.

> Additionally, `C++` has the advantage of being both an object-oriented and a **procedural language**, something very few other languages can boast of.

## Your First C++ Program
### C++ "Hello, World!" Program
In this example, we will learn to create a simple program named "Hello World" in C++ programming.

A **"Hello, World!"** is a simple program that outputs `Hello, World!` on the screen. Since it's a very simple program, it's often used to introduce a new programming language to a newbie.

Let's see how `C++` **"Hello, World!"** program works.

```C++
// My First C++ Program

#include <iostream>

int main() {
    std::cout << "Hello, World!";
    return 0;
}
```

**Output**
> **Hello, World!**

### Code Breakdown
1. `// Your First C++ Program`

In C++, any line starting with `//` is a comment. Comments are intended for the person reading the code to better understand the functionality of the program. It is completely ignored by the C++ compiler.

2. `#include <iostream>`

The `#include` is a preprocessor directive used to include files in our program. The above code is including the contents of the **iostream** file.

This allows us to use `cout` in our program to print output on the screen.

3. `int main() {...}`

A valid C++ program must have the `main()` function. The curly braces indicate the start and the end of the function.

The execution of code beings from this function.

4. `std::cout << "Hello, World!";`

`std::cout` prints the content inside the quotation marks. It must be followed by `<<` followed by the format string. In our example, `"Hello, World!"` is the format string.

**Note:** `;` is used to indicate the end of a statement.

5. `return 0;`

The `return 0;` statement is the **"Exit status"** of the program. In simple terms, the program ends with this statement.

### Things to take away
- We use `std:cout` in order to print output on the screen.
- We must include **iostream** if we want to use `std::cout.`
- The execution of code begins from the `main()` function. This function is mandatory. This is a valid `C++` program that does nothing.

```C++
int main() {
    // Write your code here
}
```

## Why Should You Use C++?
Here’s why you should know what is C++ and why to use it;

- **Fast:** Newer languages have extra bells and whistles like garbage-collection and dynamic typing, which, while helpful, slow the program's overall execution. `C++` doesn't have this additional processing overhead, so it's swift. In addition, C++ is a compiled language, contributing to the high speed.
- **Well-supported:** `C++` enjoys extensive library support, including third-party libraries, conducive to fast and rapid development.
- **Mid-level language:** That means `C++` is great for performing systems [programming](https://www.simplilearn.com/how-to-learn-programming-article) (e.g., networking, kernels, drivers), and building large-scale user applications.
- **Simple:** `Simple`, in this context, means that you can break programs down into logical units and parts. Additionally, it offers many data types and robust library support.
- **Object-oriented:** One of the C++ language’s most significant advantages is that it’s object-oriented.

> *Object-oriented* support makes it easier for `C++` to create maintainable and extensible programs.
- **Machine-independent:** Although `C++` isn’t platform-independent, it’s machine-independent. This characteristic means it can work on different computer systems regardless of their components. On the other hand, platform-independent means a Windows-compiled program won't run on a Linux system.

## Common Applications of C++
You will inevitably find the `C++` language in action no matter which way you turn. Business applications, browsers, database engines, cloud/distributed systems, game and graphics engines, and operating systems all rely on [C++ for application](https://www.simplilearn.com/c-plus-plus-programming-for-beginners-article) development since it's a versatile, general-purpose language. In addition, C++ can handle the heavy lifting of large-scale apps.

Let’s look at some areas that rely heavily on the `C++` language.

| Heading | Application |
| --- | --- |
| **Banking Applications** | Financial institutions turn to C++ for help with back-end programming. Banking applications process millions of transactions every day, thus requiring high concurrency and low latency support; C++ automatically becomes the preferred choice. |

- **Browsers**

Browser rendering engines need speed, and C++ delivers this in spades. Users want their content to appear quickly and with minimal lag, so these low-latency systems turn to C++ as their go-to programming language.

- **Cloud/Distributed Systems**

Cloud storage and distributed systems turn to C++ because they are compatible with various machines and connect exceptionally well with the hardware. In addition, the C++ language provides much-needed high concurrency and load tolerance.

- **Operating Systems**

Windows, Linux, and macOS are all programmed in C++, making the language the foundation of a good amount of our digital world. It’s not overstating matters to say that C++ is the backbone of the Internet Age.

- **Databases**

[MySQL and Postgres](https://www.simplilearn.com/tutorials/sql-tutorial/postgresql-vs-mysql), two of today’s most widely-used databases, are written in [C++ and C](https://www.simplilearn.com/tutorials/cpp-tutorial/difference-between-c-and-cpp), the latter being C++’s predecessor. These databases, in turn, are used in many of today’s most heavily-used applications, like YouTube, for example.

Here are some organizations and companies that employ the C++ language:
- Adobe
- Amazon
- Apple
- Bloomberg
- Facebook
- Google
- Microsoft
- YouTube
- Spotify

## Credits
[Resources](https://www.simplilearn.com/what-is-cpp-programming-article)

> Collaborators are acknowledged within the repository.
