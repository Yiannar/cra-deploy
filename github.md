## main

    \___________/
    branch to do some work

    How do I create a branch?
    cheeckout tells us to go to a different place
    -b is saying create a new branch
    git checkout -b <name of your branch>

    to combine add and commit use

    git commit -am "message"

    to see all branched


    git branch
    hit Q when you are done vewiing the branches

    to push to a branch

    git push origin <branch name >

git checkout <branch Name> without the b allows you to look at a branch and check it

git pull origin main

do this after you merge on github and before you add anything else to your main branch

to locally delete branch use
git branch -d <name of branch>

if you get a message that it wont delete use
git branch -D <name of branch>\

I am creating a Contact componet. I want to then push it to Github wihout my netlify updating

1- create a local branch
2- create Componets folder
3- create Contact.js
4- git status look at updates
5- git add .
6- git commit -m <message in quotes>
7- add componet to the App.js
8- npm start make sure changes are working
9- git status check everything is staged
