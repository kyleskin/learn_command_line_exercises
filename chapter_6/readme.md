#Chapter 6: LS - List Directory
Use `ls` to list the items inside a directory.

##Do More
###Describe what ls -lR does.
Typing `ls -lR` lists the contents for the rest of the directory tree and displays the read/write authority of the different users.


```
Kyles-MacBook-Air:tmp $ ls -lR

total 0
drwxr-xr-x  3 skinner  staff  102 Feb 13 15:08 stuff
   
./stuff:
total 0
drwxr-xr-x  3 skinner  staff  102 Feb 13 15:08 things
   
./stuff/things:
total 0
drwxr-xr-x  3 skinner  staff  102 Feb 13 15:08 frank
   
./stuff/things/frank:
total 0
drwxr-xr-x  3 skinner  staff  102 Feb 13 15:08 joe
   
./stuff/things/frank/joe:
total 0
drwxr-xr-x  3 skinner  staff  102 Feb 13 15:08 alex
   
./stuff/things/frank/joe/alex:
total 0
drwxr-xr-x  2 skinner  staff  68 Feb 13 15:08 john
   
./stuff/things/frank/joe/alex/john:
```

##Alternative English Questions
###1. What's in the tmp directory?
```
Kyles-MacBook-Air:tmp $ ls
stuff
```

###2. Can you show me what files are in that directory?
```
Kyles-MacBook-Air:kyleskin.github.io $ ls
LICENSE      _includes    _site        contact.html font-awesome index.html
README.md    _layouts     about.html   css          fonts        js
_config.yml  _posts       blog.html    feed.xml     img          less
```

###3. What files are in your home directory?
```
Kyles-MacBook-Air:learn_command_line_exercises $ ls ~/
Applications      Downloads         Music             RubymineProjects
Desktop           Library           Pictures          kyle-skinner-blog
Documents         Movies            Public            workspace
```

###4. What's in slash temp?
```
Kyles-MacBook-Air:learn_command_line_exercises $ ls /tmp
Atom Crashes
KSOutOfProcessFetcher.501.sAglCyxY5lzPoNgfmEvv-ZqGl-w=
com.apple.launchd.KY4bHYxNwh
com.apple.launchd.ZXN2wMrnaG
```



