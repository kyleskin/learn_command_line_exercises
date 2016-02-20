#Chapter 14: RM - Remove File
The command `rm` will remove a file or folder

##Do More
###Clean up everything in temp from all the exercises so far.
```
(master) Kyle Skinner
Kyle:chapter_14 $ ls
Gemfile      Readme.md    database.yml ex12.txt     ex13.txt

(master) Kyle Skinner
Kyle:chapter_14 $ rm Gemfile

(master) Kyle Skinner
Kyle:chapter_14 $ rm database.yml

(master) Kyle Skinner
Kyle:chapter_14 $ ls
Readme.md ex12.txt  ex13.txt
```

##Alternative English Questions
###1. Can you remove blah.txt?
```
(master) Kyle Skinner
Kyle:chapter_14 $ rm blah.txt
```

###2. Let's get rid of our development log file.
```
(master) Kyle Skinner
Kyle:chapter_14 $ rm development.log
```

###3. Can you remove everything in the slash temp slash foo directory?
```
(master) Kyle Skinner
Kyle:chapter_14 $ rm -r tmp/foo
```


