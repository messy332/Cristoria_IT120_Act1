$ git config --global user.name "messy332"
$ git config --global user.email "parparcristoria902@gmail.com"
$ git config --list
$ git config --global --list
$ history
$ dir
$ cd Desktop
$ mkdir Cristoria_IT120_Act1
$ cd Cristoria_IT120_Act1
$ git init
$ history

// To view the git init
windows + E 
Desktop
Click Cristoria_IT120_Act1
upper right click 3dots 
click view 
click show 
click hidden items

// Branch master
$ touch Profile.txt
$ touch Education.txt
$ touch Background.txt
$ touch Readme.txt
$ touch Test.py
$ git status
$ git add .
$ git status
$ history
$ nano Readme.txt
  ctrl + s
  ctrl + x
$ clear
$ nano Profile.txt
  ctrl + s
  ctrl + x
$ git status
$ nano Education.txt
  ctrl + s
  ctrl + x
$ git status
$ history
$ nano Readme.txt
  ctrl + s
  ctrl + x
$ nano Background.txt
  ctrl + s
  ctrl + x
$ nano Test.py
  ctrl; + s
  ctrl + x
$ git status
$ git add .
$ git status
$ git commit -m "First Commit"
$ git status
$ git log

//Branch main
$ git branch -m master main
$ git branch
$ history
$ nano Readme.txt
  ctrl + s
  ctrl + x
$ clear
$ git status
$ git log
  wq
$ git add Readme.txt
$ git commit -m "Adding txt on the Readme.txt"
$ git status
$ git log
$ git push --force origin main
$ git switch -c Cristoria_B1
$ git switch -c Cristoria_B2
$ git switch -c Cristoria_B3
$ git switch -c Cristoria_B4
$ nano Test.py
  ctrl + s
  ctrl + x
$ nano Readme.txt
  ctrl + s
  ctrl + x
$ git add Test.py Readme.txt
$ git commit -m "Adding a txt"
$ git status 
$ git push
$ git switch Cristoria_B1
$ nano Readme.txt
  ctrl + s
  ctrl + x
$ git commit -m "Adding a txt on the Readme.txt"
$ git push -u origin main
$ git switch Cristoria_B1

//Branch Cristoria_B1
$ nano Readme.txt
  ctrl + s   
  ctrl + x
$ git add Readme.txt
$ git commit -m "Adding text on the Readme.txt file"
$ git status
$ git log
$ git branch
$ clear
$ nano Profile.txt
$ status
$ add Profile.txt
$ git commit -m "Adding a text on the Profile.txt"
$ git status
$ clear
$ history
$ nano Readme.txt
  ctrl + s
  ctrl + x
$ git push -u origin Cristoria_B1
$ git switch main
$ nano Test.py
  ctrl + s
  ctrl + x
$ nano Readme.txt
  ctrl + s
  ctrl + x 
$ git add Test.py Readme.txt
$ git commit -m "Adding a txt on a files"
$ git push
$ git status
$ nano Readme.txt
  ctrl + s
  ctrl + x
$ git add Readme.txt
$ git commit -m "Adding a txt"
$ git push 
$ git status
$ git switch Cristoria_B2

//Branch Cristoria_B2
$ git show Cristoria_B1:Readme.txt >> Readme.txt
$ nano Education.txt
  ctrl + s  
  ctrl + x
$ nano Readme.txt
  ctrl + s  
  ctrl + x
$ git add Education.txt Readme.txt
$ git commit -m "Append on the Education.txt and Readme.txt file"
$ git status
$ nano Readme.txt
  ctrl + s  
  ctrl + x
$ git push -u origin Cristoria_B2
$ git switch main
$ nano Test.txt
  ctrl + x 
  ctrl + s
$ nano Readme.txt
  ctrl + x 
  ctrl + s
$ git add Test.py Readme.txt
$ git commit -m "Adding a text"
$ git status
$ nano Readme.txt
  ctrl + s
  ctrl + x
$ git add Readme.txt
$ git commit -m "Adding a txt"
$ git push 
$ git status
$ git switch Cristoria_B3
 

