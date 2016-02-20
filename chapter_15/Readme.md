#Chapter 15: | < > >> - Redirecting
You can use the `|`, `<`, `>`, `>>` to direct commands

##Do More
###Create some more index cards for memorizing these three symbols. Write the symbol on one side, then what it does on the other side. Drill these just like the other commands.

Done and done.

##Alternative English Questions
###Can you put "This class is fun" into bar.txt?
```
(master) Kyle Skinner
Kyle:chapter_15 $ echo "This class is fun" > bar.txt

(master) Kyle Skinner
Kyle:chapter_15 $ cat bar.txt
This class is fun
```

###Can you put "Oh so much fun" into foo.txt?
```
(master) Kyle Skinner
Kyle:chapter_15 $ echo "Oh so much fun" > foo.txt

(master) Kyle Skinner
Kyle:chapter_15 $ cat foo.txt
Oh so much fun
```

###Explain what the |, <, > and >> commands do in your own words.
* `|` Takes the output from the command on the left and puts it into the command to the right of the `|`
* `<` Takes the input from file to the right and puts it into the file on the left.
* `>` Takes the output from the command on the left and puts it into the file on the right.
* `>>` Takes the output from the command on the left and adds it to the end of the file on the right.
