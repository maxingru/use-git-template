git init
git remote add origin git@github.com:maxingru/use-git-template.git
git remote -v

git pull origin master// = fetch + merge
git fetch origin master 
git merge --no-ff -m 'init merge' origin/master --allow-unrelated-histories


//push
git push -u origin master


//branch
git switch -c dev
git branch 
git switch master
git merge --no-ff -m '' dev
git log --graph --pretty=oneline --abbrev-commit


git status
git add .
git status
git commit -m ''



git branch
git switch master
git tag -a v1.0 -m 'version 1.0 released' 1094adb
git tag		//查看所有标签
git push origin master --tags 	//push所有tags到远程


//checkout
git checkout -- file.txt
git reset;
