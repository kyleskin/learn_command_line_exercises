#Chapter 11: MV - Moving a file
`mv` allows you to file a file from one location to another

##Do More
###Move a file in the newplace directory to another directory then move it back.
```
(master) Kyle Skinner
Kyle:tmp $ mv newplace/awesome.txt third_directory/

(master) Kyle Skinner
Kyle:tmp $ ls third_directory/
awesome.txt

(master) Kyle Skinner
Kyle:tmp $ ls newplace/

(master) Kyle Skinner
Kyle:tmp $ mv third_directory/awesome.txt newplace/

(master) Kyle Skinner
Kyle:tmp $ ls newplace/
awesome.txt

(master) Kyle Skinner
Kyle:tmp $ ls third_directory/

(master) Kyle Skinner
Kyle:tmp $
```

##Alternative English Questions
###1. Can you rename foo.txt to blah.txt?
```
(master) Kyle Skinner
Kyle:tmp $ mv foo.txt blah.txt

(master) Kyle Skinner
Kyle:tmp $ ls
blah.txt          neat.txt          something         third_directory
iamcool.txt       newplace          thefourthfile.txt uncool.txt
```

###2. Can you move the production.log file in the log directory to slash temp?
```
(master) Kyle Skinner
Kyle:chapter_11 $ mv log/production.log /temp
```
