Making file in Bash:


touch example.?ie		// create file name example.?ie extension of .?ie or anything
git add example.?ie		// add file
git commit -m "describe file"	// add commit describtion of file
git push -u origin master	// upload file to git


Create a new repository on the command line

touch README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/tgifang/tgifang.github.io.git
git push -u origin master


Push an existing repository from the command line

git remote add origin https://github.com/tgifang/tgifang.github.io.git
git push -u origin master
