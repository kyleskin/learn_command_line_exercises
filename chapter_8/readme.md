#Chapter 8: PUSHD & POPD - Moving around between directories
Use `pushd` & `popd` to move between directories.

##Do More
###Use these commands to move around directories all over your computer.
```
(master) Kyle Skinner
Kyles-MacBook-Air:chapter_8 $ pushd ~/Desktop/blog-final/
~/Desktop/blog-final ~/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_8 ~/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_8/temp

(master) Kyle Skinner
Kyles-MacBook-Air:blog-final $ popd
~/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_8 ~/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_8/temp

(master) Kyle Skinner
Kyles-MacBook-Air:chapter_8 $
```

###Remove the i/like/icecream directories and make your own, then move around in them.
```
(master) Kyle Skinner
Kyles-MacBook-Air:temp $ rmdir -p i/like/icecream/
```

```
(master) Kyle Skinner
Kyles-MacBook-Air:chapter_8 $ mkdir -p temp/stuff/things/frank/joe/alex/john

(master) Kyle Skinner
Kyles-MacBook-Air:chapter_8 $ cd temp/

(master) Kyle Skinner
Kyles-MacBook-Air:temp $ pushd stuff/things/
~/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_8/temp/stuff/things ~/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_8/temp ~/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_8/temp

(master) Kyle Skinner
Kyles-MacBook-Air:things $ pushd ~/workspace/davinci_coders_t1_2016/
~/workspace/davinci_coders_t1_2016 ~/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_8/temp/stuff/things ~/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_8/temp ~/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_8/temp


Kyles-MacBook-Air:davinci_coders_t1_2016 $ popd
~/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_8/temp/stuff/things ~/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_8/temp ~/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_8/temp

(master) Kyle Skinner
Kyles-MacBook-Air:things $ popd
~/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_8/temp ~/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_8/temp

(master) Kyle Skinner
Kyles-MacBook-Air:temp $
```

###Explain to yourself the output that pushd and popd print out to you.
`pushd *directory name*` switches you into that directory and gives the output detailing first the directory path of where you're moving to and then the directory path of where you moved from.

`popd` details the directory path you just moved into and then the next directory path left in your stack.
