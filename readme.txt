How to Install GIT

*download from here
http://sourceforge.net/projects/gitextensions/

*follow this to set ssh keys
https://help.github.com/articles/generating-ssh-keys/

for some reason, this line does not work:
ssh-agent -s
but this line does:
eval $(ssh-agent)


fyi - you are supposed to call your online repo "origin" when you are on your local account
so you may see examples referring to origin, this just means your online acct.

*set proxy server from gitbash (git extensions ->tools ->git bash)
git config --global http.proxy http://wwwcache.rl.ac.uk:8080/

*to pull my sample repo
be in a blank or empty repo or no repo at all (don't have any of your code on the screen)
you can pull or clone, pretty much does the same thing at this point.
to clone:
start -> clone repository
repo to clone = https://github.com/StephanieSullivan/Sandbox
set a destination on your computer, probably a good idea to have 1 folder for all git projects
for branch, try to leave blank, pick master if you are forced to choose

to pull:
click commands ->pull
click the top right button to manage remotes
pick any name you will remember
url = https://github.com/StephanieSullivan/Sandbox