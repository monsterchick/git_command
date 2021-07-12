There are some common commands to be quickly checked and also let me bring back the memory. 

1.git init

2.git add filename / add .

3.git commit -m "first commit" 
git status (to check if the file commited)
git rm --cached file (recover the file from commited status)

4.git remote add origin url
git remote -v (to see what remote links there are)

5.git push -u origin master ("-u" means that there is no need to type "origin master" anymore)


git clone url newname (give a new name to avoid repeat the folder name)
===>>cd newname
===>> change content and push
===>> cd ..
===>> git pull (because local:old code, remote: new code)
