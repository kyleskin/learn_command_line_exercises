#Chapter 17: FIND - Finding files
`find STARTDIR -name WILDCARD -print` will find a file and print the output

##Do More
###Get your find index card and add this to the description side: "find STARTDIR -name WILDCARD -print".

Done and done.

###You can put any directory where the . (dot) is. Try another directory to start your search there.
```
(master) Kyle Skinner
Kyle:chapter_17 $ find ../chapter_13/ -name "*.txt" -print
../chapter_13//tmp/ex12.txt
../chapter_13//tmp/ex13.txt
../chapter_13//tmp/ex13again.txt
```

###Look for all the video files on your computer starting at the home drive and use the > to save the list to a file.
```
(master) Kyle Skinner
Kyle:chapter_17 $ find ~/ -name "*.mp4" > video_list.txt

(master) Kyle Skinner
Kyle:chapter_17 $ cat video_list.txt
/Users/skinner//.rvm/src/ruby-2.2.4/sample/trick2013/mame/music-box.mp4
/Users/skinner//workspace/davinci_videos/in_class/anki_intro_posse_cup.mp4
/Users/skinner//workspace/davinci_videos/in_class/building_your_brand_wordpress_intro.mp4
/Users/skinner//workspace/davinci_videos/in_class/git_101.mp4
/Users/skinner//workspace/davinci_videos/in_class/git_101_warmup.mp4
/Users/skinner//workspace/davinci_videos/in_class/git_102.mp4
/Users/skinner//workspace/davinci_videos/in_class/intro_to_agile.mp4
/Users/skinner//workspace/davinci_videos/in_class/learn_command_line_part_1.mp4
/Users/skinner//workspace/davinci_videos/in_class/learn_command_line_part_2.mp4
/Users/skinner//workspace/davinci_videos/in_class/lrthw_intro.mp4
/Users/skinner//workspace/davinci_videos/in_class/making_it_stick.mp4
/Users/skinner//workspace/davinci_videos/in_class/mentorship_intro.mp4
/Users/skinner//workspace/davinci_videos/in_class/pair_programming.mp4
/Users/skinner//workspace/davinci_videos/in_class/pivotal_tracker_intro.mp4
/Users/skinner//workspace/davinci_videos/in_class/questions_gitignore_mine_autocomplete.mp4
/Users/skinner//workspace/davinci_videos/in_class/rescuetime_and_slack_intros.mp4
/Users/skinner//workspace/davinci_videos/in_class/toolbelt_intro.mp4
/Users/skinner//workspace/davinci_videos/in_class/tracker_warmup_and_posses.mp4
```

##Alternative English Questions
###1. Can you show me all the files in slash temp slash foo?
```
(master) Kyle Skinner
Kyle:chapter_17 $ find temp/foo/ -print
```

###2. What log files are in your log directory?
```
(master) Kyle Skinner
Kyle:chapter_17 $ find log/ -name "*.log" -print
log//four.log
log//one.log
log//three.log
log//two.log
```

###3. Run find in the class directory, pipe the output to pbcopy and create a gist with the content.
```
(master) Kyle Skinner
Kyle:chapter_17 $ find ../../.. | pbcopy
```

[Output Gist](https://gist.github.com/kyleskin/84c84b028c4b4e840179)
