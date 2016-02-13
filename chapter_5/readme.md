#Chapter 5: CD - Change Directory
Typing `cd *directory name*` moves you into a directory.

##Do More
###cd to the joe directory with one command.
`Kyles-MacBook-Air:chapter_4 $ cd temp/stuff/things/frank/joe/`

`Kyles-MacBook-Air:joe $`

###cd back to temp with one command, but not further above that.
`Kyles-MacBook-Air:joe $ cd ../../../..`

`Kyles-MacBook-Air:temp $`

###Find out how to cd to your "home directory" with one command.
`Kyles-MacBook-Air:temp $ cd ~`

`Kyles-MacBook-Air:~ $`

###cd to your Documents directory, then find it with your GUI file browser (Finder, Windows Explorer, etc.).
`Kyles-MacBook-Air:~ $ cd Documents`

`Kyles-MacBook-Air:Documents $`

To find this with my GUI file browser, in this case Finder, is very simple.  When I click on Finder and open a new window, it defaults to displaying my home folder.  From there, I can either choose the ***Documents*** folder shortcut that I have on the left side of the window, or I locate it in the list of folders in the main section of the window. 

###cd to your Downloads directory, then find it with your file browser.
`Kyles-MacBook-Air:Documents $ cd ~/Downloads/`

`Kyles-MacBook-Air:Downloads $`

Again, this is very easy to do with the GUI browser.  When I open a new finder window, I can find the ***Downloads*** directory either as a shortcut on the left of the window, or in the main section of the window.

###Find another directory with your file browser, then cd to it.
I'm going to be creating a new post page on my blog. In my file browser, I first open my ***Desktop*** folder by clicking on the small triangle to the left of the directory.  From there I open ***blog-final***, then ***kyleskin.github.io***, then finally ***posts***.

To do this with the command line, I type the following:

`Kyles-MacBook-Air:~ $ cd Desktop/blog-final/kyleskin.github.io/_posts/`

`Kyles-MacBook-Air:_posts $`

##Alternative English Questions
###1. Can you cd into the temp directory?
`Kyles-MacBook-Air:~ $ cd workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_4/temp/`

`Kyles-MacBook-Air:temp $`

###2. Why don't we go into the temp directory?
`Kyles-MacBook-Air:~ $ cd workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_4/temp/`

`Kyles-MacBook-Air:temp $`

###3. Can you go to the slash temp directory?
`Kyles-MacBook-Air:chapter_5 $ cd /tmp`

`Kyles-MacBook-Air:tmp $`

###4. Can you go to the slash temp slash log directory?
`Kyles-MacBook-Air:~ $ cd /temp/log`

`Kyles-MacBook-Air:log $`

###5. What does the .. argument to cd do?
Typing `cd ..` moves you up a directory.  So, for example, I'm currently in ***/Users/skinner/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_5***.  Typing `cd ..` will move us to ***learn_command_line_exercises***.

`Kyles-MacBook-Air:chapter_5 $ cd ..`

`Kyles-MacBook-Air:learn_command_line_exercises $`
