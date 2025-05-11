# Report

1. In C, do you use printf or print? 

2. What operating system do you use? 

3. Explain the `-Wall` option for your C compiler. 


    3a. Copy and paste the `SYNOPSIS` section from the gcc manual page (Hint: what is the linux command to get this?). Make sure to use a preformatted text block below 

        ```
        copy and paste here
        ```

4. How would you list all files in a directory using the long format, but exclude the `.`. and `..` file?

    ```console
    $ (put your command here after $ sign, with space), example: $ cd ..
    ```

5. Complete the table below based on linux permission sets for files.

    | Permission |  Owner             | Group               | World               | Directory? |  
    | ---------- | ------------------ | ------------------  | ------------------  | ---------- |
    | -rw-r--r-- | read,write         |  read               | read                |  no        |
    | -rwx------ | read,write,execute |  none               | none                |  no        |
    | -r--r--r-- |                    |                     |                     |            |
    | drwxr-xr-x |                    |                     |                     |            |
    |            | read,write         | read,write          | none                |  no        |
    |            | read,execute       | execute             | execute             |  yes       |


     

6. Permissions for files are often set by binary values. For example 111 is read, write, execute. When all of them are converted and put together, that is an octal. For example: `700` is `rwx------` or `644` is `rw-r--r--` (common for web pages).  
   Convert the following numeric representation to permissions. 

   | Octal |  Binary     | Permission |
   |  ---  |  ---------- | ---------- |
   |  700  |  111000000  | rwx------  |
   |  644  |  110100100  | rw-r--r--  |
   |  444  |             |            |    
   |  622  |             |            |
   |  660  |             |            |
   |  770  |             |            |
   |  111  |             |            |

> While we rarely will deal with permissions in this course, the above was to help you practice thinking about how to represent information. 

7. Pick three linux commands. List them below using bullets (inset under this number). In your own words describe what each command does. 
   
   * example: ls - lists directory contents
   * 
   * 
   *    

8. Fix the following C code. You are free to write a small program to help figure it out. 
    ```c
    int input
    scanf("%d", input)
    printf("The answer to the question is: %d\n", input);
    ```

9. In line two of the three C code lines above, what is being passed into scanf? Is it the value or is it the address of a memory location?


10. Thinking back to CS 5001 - you should have briefly covered a linear and binary search algorithms. 

    10a. In your own words describe a linear search algorithm.

    Don't forget to match your indent on your answer (delete this line..)


    10b. In your own words describe a binary search algorithm. 


    10c. Which one is faster? And is it situational?


Note: if you didn't cover them, that is fine! Whether you covered them or not, I would like you to look up at least two (2) references for them online, and include a citation of that reference in your answer. Below is an example of the expected format.

---

Strings in C are sequences of characters stored in an array structure, ended by the null terminator [1]. In order to use them, most systems provide access to <string.h> to provide functions such as `strlen()` and `strcpy()` [2].

---

## Deeper Thinking

Computer science ends up becoming more "exploration" based as you progress. This assignment required a lot of exploration and learning the correct thing to setup / install - which is all unique based on your systems. This is common in the industry, even if it can be frustrating for a student just learning. 
  
Reflect a bit on why that would be the case for computer science? Include in your reflection some "habits" you can develop to help better that process of exploration and learning. Please include at least a paragraph for this reflection. You should not just give your answer with bullet points. Doing so will have it returned. Prose writing is important. While you can include proper use of bullet points in prose, you still need to format your writing as a paragraph!  



## References
Place your references here using [ACM format](https://www.acm.org/publications/authors/reference-formatting). Hint: if you are unsure how to format something, this is a good case of using [claude](https://claude.northeastern.edu/) or other LLM - you can paste it in and ask it to format the link into ACM format. If you can't find all the info, we won't hold you to strict formatting, just a proper attempt. 

1. GeeksforGeeks. 2025. Strings in C. (January 10, 2025). Retrieved April 5, 2025 from https://www.geeksforgeeks.org/strings-in-c/
 
2. GeeksforGeeks. 2025. C String Functions. (January 17, 2025). Retrieved April 5, 2025 from https://www.geeksforgeeks.org/string-functions-in-c/
