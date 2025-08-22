# Demo

we will add here anything that we learn, like how "#" in the .md file creates header, .md are markdown files things like that.

commiting changes things. and we can see the history of commits.
# Source
https://www.youtube.com/watch?v=RGOj5yH7evk

## Subheader
we need to create SSH in the machinge and add them on github, to be able to get the data from github. 

all files that has U, in the side means that they are untracked by git, for them to be tracked we need to add them using git add command, 
git add . adds all
git add "filename" adds the specific filename 

git status will tell you if there are changes and if there are files taht are untracked, files need to be saved locally to count as modified (files with M in the side)

to commit the changes use the command git commit -m "message her" ::-m means message and you need to add the message for the commit to happen and the message ideally tells what happened
 so this will only save things locally, but is not live on github yet. 

to get it live to github, you nedd to use another command, git push
in this process we need ssh key, this proves to github that you are the owner of the account, to do this you will need to create an ssh key in you machine and add that to github.

git push origin master

alright, so we always nee to add, commit and push
git add stages the changes that has been made, commit makes the changes in the local machine and push applies the changes in github


now on to branches:
to see what are the branches, you use:
git branch
to create a new branch:
git checkout -b name_branch
to switch between branches we also use
git checkout

to compare different branches we use:
git diff branch-nameto compare

to merge branches we use
git merge

before merging, the most common thing to do is to puch it in github, then create a pull request (PR), this is the std since most of the time the file is not yours and multiple people work on it

once we made PR, people can review it and make comments. they you can make changes and edits based on the comments, commit and once everything is good, the PR can be approved, the branches will be merged and the branch will be gone, then you can create a new branch for edits and start it over again.

