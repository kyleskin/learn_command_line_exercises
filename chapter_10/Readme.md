#Chapter 10: CP - Copy a File
To create a copy of an existing file, use the command `cp`

##What is Robocopy?
Robocopy, or robust copy, is a Microsoft DOS command for copying files, directories, or even drives.

##Do More
###Use the cp -r command to copy more directories with files in them.
```
(master) Kyle Skinner
Kyle:tmp $ cp -r newplace/ third_directory

(master) Kyle Skinner
Kyle:tmp $ ls
awesome.txt       neat.txt          something         third_directory
iamcool.txt       newplace          thefourthfile.txt
```

###Copy a file to your home directory or desktop
```
(master) Kyle Skinner
Kyle:tmp $ cp iamcool.txt ~/Desktop/

(master) Kyle Skinner
Kyle:tmp $ ls ~/Desktop/
Learn to Program, 2nd Edition.pdf iamcool.txt
blog-final                        kyle-skinner-blog
```

###Find these files in your graphical user interface and open them in a text editor.
This is done very easily by open a new finder window and following my directory tree.  I used TextEdit to open the file and verify the example text I had placed in them was there.

##Alternative English Questions
###1. Can you copy the foo.txt file to slash temp? (Create foo.txt first...)
```
(master) Kyle Skinner
Kyle:chapter_10 $ echo "Foobar" > foo.txt

(master) Kyle Skinner
Kyle:chapter_10 $ cp foo.txt tmp/

(master) Kyle Skinner
Kyle:chapter_10 $ ls tmp
awesome.txt       iamcool.txt       newplace          thefourthfile.txt
foo.txt           neat.txt          something         third_directory
```

###2. Can you copy .bash_profile in your home directory to the current directory?
```
(master) Kyle Skinner
Kyle:chapter_10 $ cp /Users/skinner/.bash_profile .

(master) Kyle Skinner
Kyle:chapter_10 $ ls -a
.             ..            .bash_profile Readme.md     foo.txt       tmp
```


