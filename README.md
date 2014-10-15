git-goodies
===========

-----

## Installation

1 - Clone the repo in your home folder.

```
cd ~
git clone https://github.com/javiscriptme/git-goodies.git
```

2 - Add the following lines to your ```~/.bashrc```* file.

\* ```~/.bash_profile``` In OSX systems. 

```
PATH=$PATH:$HOME/git-goodies
export PATH
```

3 - For the commands to work, close and open the terminal

or execute: ```source ~/.bashrc```

---

## Reference

> ```git wip```

Creates a commit with the changes from your working directory and/or staging area setting the commit message to ```*** WIP```.

> ```git unwip```

Removes a previously 'wipped' commit applying a default reset ( keeping changes in the working directory )

> ```git divlog [branch1 = HEAD] [branch2 = master]```

Shows which commits are in branch1 and not in branch2 and viceversa. Parameters are optional, by default ```branch1``` is ```HEAD``` and ```branch2``` is ```master```.
