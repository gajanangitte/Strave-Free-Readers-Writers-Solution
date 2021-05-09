# Strave-Free-Readers-Writers-Solution
This repository aims to provide a solution for strave free reader-writer problem or the 3rd reader writers problem.

## Basics

### First Readers-Writers Problem
The first reader writer problem involves giving priority to readers. Thus, potentially starving writers. 
> *no reader shall be kept waiting if the share is currently opened for reading.*

### Second Readers-Writers Problem
The second reader writer problem involved giving priority to readers. Thus, potentially starving readers. This problem acknowledges presence of multiple writers. 
> *no writer, once added to the queue, shall be kept waiting longer than absolutely necessary.*

### Third Readers-Writers Problem
***Starve Free Solution***
> *no thread shall be allowed to strave*

## Use

### Linux or C solution
`g++ stravefree.c -lpthread -o c_output && ./c_output && rm c_output`

### C++ solution
`g++ stravefree.c -pthread -o cpp_output -std=c++11 && ./cpp_output && rm cpp_output`
