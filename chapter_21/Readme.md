#Chapter 21: ENV, ECHO - What's In Your Environment?
`env` shows the environment variabels and `echo` will print arguments
 
##Do More
###I want you to go online and research how you change your PATH for your computer. Try to do it entirely from the CLI.
```
(master) Kyle Skinner
Kyle:chapter_21 $ echo $PATH
/Users/skinner/.rvm/gems/ruby-2.2.3/bin:/Users/skinner/.rvm/gems/ruby-2.2.3@global/bin:/Users/skinner/.rvm/rubies/ruby-2.2.3/bin:/usr/local/bin:/usr/bin:/bin:/usr/sbin:/sbin:/Users/skinner/.rvm/bin

(master) Kyle Skinner
Kyle:chapter_21 $ export PATH=$PATH:~/opt/bin:~/dev/bin

(master) Kyle Skinner
Kyle:chapter_21 $ echo $PATH
/Users/skinner/.rvm/gems/ruby-2.2.3/bin:/Users/skinner/.rvm/gems/ruby-2.2.3@global/bin:/Users/skinner/.rvm/rubies/ruby-2.2.3/bin:/usr/local/bin:/usr/bin:/bin:/usr/sbin:/sbin:/Users/skinner/.rvm/bin:/Users/skinner/opt/bin:/Users/skinner/dev/bin
```

##Alternative English Questions
###1. What is your shell set to?
```
(master) Kyle Skinner
Kyle:chapter_21 $ env | grep -i shell
SHELL=/bin/bash
```

###2. What directory are you in (don't use pwd this time)?
```
(master) Kyle Skinner
Kyle:chapter_21 $ env | grep -i path
rvm_bin_path=/Users/skinner/.rvm/bin
rvm_path=/Users/skinner/.rvm
PATH=/Users/skinner/.rvm/gems/ruby-2.2.3/bin:/Users/skinner/.rvm/gems/ruby-2.2.3@global/bin:/Users/skinner/.rvm/rubies/ruby-2.2.3/bin:/usr/local/bin:/usr/bin:/bin:/usr/sbin:/sbin:/Users/skinner/.rvm/bin:/Users/skinner/opt/bin:/Users/skinner/dev/bin
GEM_PATH=/Users/skinner/.rvm/gems/ruby-2.2.3:/Users/skinner/.rvm/gems/ruby-2.2.3@global
```

###3. What is your home directory set to?
```
(master) Kyle Skinner
Kyle:chapter_21 $ env | grep -i home
GEM_HOME=/Users/skinner/.rvm/gems/ruby-2.2.3
OLDPWD=/Users/skinner/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises
MY_RUBY_HOME=/Users/skinner/.rvm/rubies/ruby-2.2.3
PWD=/Users/skinner/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_21
HOME=/Users/skinner
```

###4. Can you set your environment to have DEBUG set to true?
```
(master) Kyle Skinner
Kyle:chapter_21 $ export DEBUG=$DEBUG: true

(master) Kyle Skinner
Kyle:chapter_21 $ echo $DEBUG
true:
```

