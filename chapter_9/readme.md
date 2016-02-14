#Chapter 9: TOUCH - Create an Empty File
Type `touch *file.name*` to create an empty file

##Do More
###Make a directory, change to it, and then make a file in it. Then change one level up and run the rmdir command in this directory. You should get an error. Try to understand why you got this error.
```
(master) Kyle Skinner
Kyles-MacBook-Air:learn_command_line_exercises $ mkdir chapter_9

(master) Kyle Skinner
Kyles-MacBook-Air:learn_command_line_exercises $ cd chapter_9/

(master) Kyle Skinner
Kyles-MacBook-Air:chapter_9 $ touch readme.md

(master) Kyle Skinner
Kyles-MacBook-Air:learn_command_line_exercises $ rmdir chapter_9/
rmdir: chapter_9/: Directory not empty
```

A simple `rmdir *directory name*` doesn't work because there is a file inside that directory.

##Alternative English Questions
###1. Can you touch blah.txt?
```
(master) Kyle Skinner
Kyles-MacBook-Air:chapter_9 $ touch blah.txt
```

###2. Let's create foo.txt.
```
(master) Kyle Skinner
Kyles-MacBook-Air:chapter_9 $ touch foo.txt
```

##What happens if you touch an existing file?
Touching an existing file will change its access time, modification time, or both.
