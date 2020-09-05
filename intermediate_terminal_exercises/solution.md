# Intermediate Terminal Exercises
## Part 1

### 5. Why would you want to create an environment variable?
I want to create an environment variable so that i can easily access a file, without typing the entire absolute directory.

### 6. How do you permanently save environment variables?
by adding the following comand to your bashrc file or .profile in your Linux Terminal

```bash
 export <PATHENAME>=/Users/tim/<PATH_YOU_WANT_TO_SAVE>
 EXPORT PATH
```

### 7. What is a process?
A process is the instance of running a program on your computer.

### 8. How do you list all processes running on your machine?
By putting the below comand on your terminal
```bash
ps aux
```
### 9. What is a PID?
PID represents Process Identifiction Number. This is a number automatically assigned to a process.

### 10. How do you terminate a process?
By using the kill <PID> or kill -9 <PID>

### 11. What is the difference between kill and kill -9?
kill will send an instruction to the program regquesting it to quit, while kill -9 will force the program to quit.

### 12. What grep flag allows for case insensitive search?

     -i 

### 13. What grep flag allows for a certain number of lines before the match?
    -B

### 14. What grep flag allows for a certain number of lines around the match?
    -C

### 15. What grep flag allows for a certain number of lines after the match?
    -A

### 16. What grep flag allows for full word search?
    -w

### 17. What grep flag shows you the line number of a match?
    -n

