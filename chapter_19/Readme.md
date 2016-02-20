#Chapter 19: MAN - Display manuals
`man COMMAND_NAME` will display help information about the command

##Do More
###Use man or help to look at every one of the commands you have in your list to memorize.

Done and done.

##Alternative English Questions
###1. What option to ls tells it to output file size in human readable form?
```
(master) Kyle Skinner
Kyle:learn_command_line_exercises $ man ls

-h      When used with the -l option, use unit suffixes: Byte, Kilobyte,
             Megabyte, Gigabyte, Terabyte and Petabyte in order to reduce the
             number of digits to three or less using base 2 for sizes.
             
(master) Kyle Skinner
Kyle:learn_command_line_exercises $ ls -lh
total 8
-rw-r--r--   1 skinner  staff    75B Feb 20 10:31 README.md
drwxr-xr-x   3 skinner  staff   102B Feb 12 00:28 chapter_1
drwxr-xr-x   6 skinner  staff   204B Feb 16 09:11 chapter_10
drwxr-xr-x   6 skinner  staff   204B Feb 16 09:44 chapter_11
drwxr-xr-x   7 skinner  staff   238B Feb 16 20:08 chapter_12
drwxr-xr-x   5 skinner  staff   170B Feb 20 09:55 chapter_13
drwxr-xr-x   7 skinner  staff   238B Feb 20 09:55 chapter_14
drwxr-xr-x  10 skinner  staff   340B Feb 20 09:55 chapter_15
drwxr-xr-x   5 skinner  staff   170B Feb 20 09:55 chapter_16
drwxr-xr-x   8 skinner  staff   272B Feb 20 10:29 chapter_17
drwxr-xr-x   6 skinner  staff   204B Feb 20 11:09 chapter_18
drwxr-xr-x   3 skinner  staff   102B Feb 20 11:20 chapter_19
drwxr-xr-x   5 skinner  staff   170B Feb 16 09:10 chapter_2
drwxr-xr-x   3 skinner  staff   102B Feb 15 17:55 chapter_3
drwxr-xr-x   5 skinner  staff   170B Feb 13 13:40 chapter_4
drwxr-xr-x   5 skinner  staff   170B Feb 17 20:52 chapter_5
drwxr-xr-x   5 skinner  staff   170B Feb 19 18:32 chapter_6
drwxr-xr-x   3 skinner  staff   102B Feb 13 17:02 chapter_7
drwxr-xr-x   5 skinner  staff   170B Feb 16 09:10 chapter_8
drwxr-xr-x   6 skinner  staff   204B Feb 13 19:49 chapter_9
```

###2. Is there a case insensitive option to grep?
```
(master) Kyle Skinner
Kyle:learn_command_line_exercises $ man grep

-i, --ignore-case
             Perform case insensitive matching.  By default, grep is case sensi-
             tive.
             
(master) Kyle Skinner
Kyle:chapter_18 $ grep -i "kyle skinner" *.txt
name.txt:Kyle Skinner
```

###3. What does the -r and -f options to rm do exactly?
```
(master) Kyle Skinner
Kyle:learn_command_line_exercises $ man rm

    -f          Attempt to remove the files without prompting for confirmation,
                 regardless of the file's permissions.  If the file does not
                 exist, do not display a diagnostic message or modify the exit
                 status to reflect an error.  The -f option overrides any previ-
                 ous -i options.
                 
    -R          Attempt to remove the file hierarchy rooted in each file argu-
                  ment.  The -R option implies the -d option.  If the -i option is
                  specified, the user is prompted for confirmation before each
                  directory's contents are processed (as well as before the
                  attempt is made to remove the directory).  If the user does not
                  respond affirmatively, the file hierarchy rooted in that direc-
                  tory is skipped.
     
    -r          Equivalent to -R.
```

`-f` removes file regardless of permissions.  `-r` removes the directories in the file's hierarchy.

###4. What does the ifconfig command do?
```
(master) Kyle Skinner
Kyle:learn_command_line_exercises $ man ifconfig

  ifconfig -- configure network interface parameters
```
