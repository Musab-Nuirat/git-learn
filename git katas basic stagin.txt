## What's the content of file.txt? 
1

## Overwrite the content in file.txt: echo 2 > file.txt to change the state of your file in the working directory 
## What does git diff tell you?
The file.txt has been modified from 1 to 2 

## What does git diff --staged tell you? why is this blank?
nothing

## Run git add file.txt to stage your changes from the working directory.
## What does git diff tell you?
nothing

## What does git diff --staged tell you?
the file.txt has been modified from the last staged status to now, from 1 to 2 

## Overwrite the content in file.txt: echo 3 > file.txt to change the state of your file in the working directory 
## What does git diff tell you?
the file.txt has been modified from 2 to 3 

## What does git diff --staged tell you?
the file.txt has been modified from the last staged status to now, from 1 to 2 

## Explain what is happening

## Run git status and observe that file.txt are present twice in the output.
yes, the first saying that the file should be committed, and the second saying that the changes not staged yet

## Run git restore --staged file.txt to unstage the change
## What does git status tell you now?
it restore the status of the file.txt in the staging area, so now only the second msg remains in the git status (changes not staged yet)

## Stage the change and make a commit
## What does the log look like?
It will show the details of the commit i have just made.
It will include the commit hash, author, date, and the commit message.

## Overwrite the content in file.txt: echo 4 > file.txt
## What is the content of file.txt?
4

## What does git status tell us?
The file.txt not been staged yet

## Run git restore file.txt
## What is the content of file.txt?
3

## What does git status tell us?
there is nothing to be committed 
