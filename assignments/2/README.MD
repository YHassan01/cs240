# Requirements

1. Answer Part 1 questions here in this file
2. Answer Part 2 questions in the source files
3. Submit this file and the two source files on to the Gradescope

# Part1: Short Answer Questions

### 1. Called by Value (10 Points)
What it means called by value in C? values being passed when arguments are integer and char array respectively?
      **Answer**: A function's formal parameter is set to the argument's address when it is called by reference. Therefore, the argument is affected by changes made to the parameter inside the function. Changing the value of a function's formal argument, such as an int variable, causes a corresponding change in the original variable.

  

### 2. Scope (10 Points)
What is the scope of a variable in C? 
    **Answer**: When the data type and declared name of an object are known within a block or source file, the object is visible. Scope refers to the area where an object is visible



4.) key word *extern* in C?
     **Answer**: the usage of the External variables are more convenient and efficient when there are many variables to share between functions. After a function call has exited, external variables retain their values. For accessing an external variable that is not defined within this source code, we have to use the "extern" keyword.


### 3. Static (10 Points)

What is the static key word means for an external and an internal variable?

**Answer**:

### 4. Commandline Arguments (10 Points)

How to use commandline arguments in C? Give an example.
      **Answer**: During the execution of a command, the user provides arguments via the command line of the operating system.
ex: int main(int argc, char *argv[]); 

# Part2: Coding  (60 Points)

Read the question in the README file and then complete the [solution] function
in the Source Code file for submission.

Coding 1: [README](coding
_1.MD) and [Source Code](coding_1.c)

Coding 2: [README](Coding_2.MD) and [Source Code](coding_2.c)
