#Chapter 7: RMDIR - Remove Directory
Use `rmdir *directory name*` to remove the directory below where you are in the directory tree.

##Do More
###Make 20 more directories and remove them all.
I used `mkdir delete_me` to create a directory called ***delete_me*** and then `rmdir delete_me` to remove it twenty times. 

```
(master) Kyle Skinner
Kyles-MacBook-Air:tmp $ mkdir delete_me

(master) Kyle Skinner
Kyles-MacBook-Air:tmp $ rmdir delete_me/
```

###Make a single path of directories that is 10 deep and remove them one at a time.
```
(master) Kyle Skinner
Kyles-MacBook-Air:tmp $ mkdir -p one/two/three/four/five/six/seven/eight/nine/ten

(master) Kyle Skinner
Kyles-MacBook-Air:tmp $ cd one/two/three/four/five/six/seven/eight/nine/ten/

(master) Kyle Skinner
Kyles-MacBook-Air:ten $ cd ..

(master) Kyle Skinner
Kyles-MacBook-Air:nine $ rmdir ten

(master) Kyle Skinner
Kyles-MacBook-Air:nine $ cd ..

(master) Kyle Skinner
Kyles-MacBook-Air:eight $ rmdir nine

(master) Kyle Skinner
Kyles-MacBook-Air:eight $ cd ..

(master) Kyle Skinner
Kyles-MacBook-Air:seven $ rmdir eight

(master) Kyle Skinner
Kyles-MacBook-Air:seven $ cd ..

(master) Kyle Skinner
Kyles-MacBook-Air:six $ rmdir seven

(master) Kyle Skinner
Kyles-MacBook-Air:six $ cd ..

(master) Kyle Skinner
Kyles-MacBook-Air:five $ rmdir six

(master) Kyle Skinner
Kyles-MacBook-Air:five $ cd ..

(master) Kyle Skinner
Kyles-MacBook-Air:four $ rmdir five

(master) Kyle Skinner
Kyles-MacBook-Air:four $ cd ..

(master) Kyle Skinner
Kyles-MacBook-Air:three $ rmdir four

(master) Kyle Skinner
Kyles-MacBook-Air:three $ cd ..

(master) Kyle Skinner
Kyles-MacBook-Air:two $ rmdir three

(master) Kyle Skinner
Kyles-MacBook-Air:two $ cd ..

(master) Kyle Skinner
Kyles-MacBook-Air:one $ rmdir two

(master) Kyle Skinner
Kyles-MacBook-Air:one $ cd ..

(master) Kyle Skinner
Kyles-MacBook-Air:tmp $ rmdir one
```

##Alternative English Questions
###1. Can you remove the tmp directory?
```
(master) Kyle Skinner
Kyles-MacBook-Air:chapter_7 $ rmdir tmp
```

###2. Let's remove the tmp directory.
```
(master) Kyle Skinner
Kyles-MacBook-Air:chapter_7 $ rmdir tmp
```
