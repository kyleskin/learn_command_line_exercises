#Chapter 18: GREP - Looking Inside Files
`grep` allows you to search inside files

##Do More
###Use quotes to find "new file" and "old file" and "This is".
```
(master) Kyle Skinner
Kyle:chapter_18 $ grep "new file" *.txt
newfile.txt:This is a new file.
newfile.txt:This is a new file.
newfile.txt:This is a new file.

(master) Kyle Skinner
Kyle:chapter_18 $ grep "old file" *.txt
oldfile.txt:This is a old file.
oldfile.txt:This is a old file.
oldfile.txt:This is a old file.

(master) Kyle Skinner
Kyle:chapter_18 $ grep "This is" *.txt
newfile.txt:This is a new file.
newfile.txt:This is a new file.
newfile.txt:This is a new file.
oldfile.txt:This is a old file.
oldfile.txt:This is a old file.
oldfile.txt:This is a old file.
```

###Take the list of videos you created (or any other list) and use it to find some videos you want to find.
```
(master) Kyle Skinner
Kyle:chapter_18 $ grep "music-box.mp4" ../chapter_17/video_list.txt
/Users/skinner//.rvm/src/ruby-2.2.4/sample/trick2013/mame/music-box.mp4
```

##Alternative English Questions
###1. Show me the lines in foo.txt that have "ERROR" in them.
```
(master) Kyle Skinner
Kyle:chapter_18 $ grep ERROR foo.txt
```

###2. Show me the lines in bar.txt that have "davinci" in them.
```
(master) Kyle Skinner
Kyle:chapter_18 $ grep davinci bar.txt
```

###3. Can you print all the lines in text files that have your first and last name in them?
```
(master) Kyle Skinner
Kyle:chapter_18 $ grep "Kyle Skinner" *.txt
name.txt:Kyle Skinner
```

##Add a comment that explains what the -i option to grep accomplishes.
`-i` ignores case in the search
```
(master) Kyle Skinner
Kyle:chapter_18 $ grep -i "kyle skinner" *.txt
name.txt:Kyle Skinner
```

