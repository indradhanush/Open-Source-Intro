GIT : 

Install Git : 

sudo apt-get install git

Setup Git : 

git config --global user.name "Your Name"

git config --global user.email "your_email@example.com"

Password Caching : 

git config --global credential.helper 'cache --timeout=3600'


Create a Repository :

mkdir Hello

cd Hello

git init

touch README.md

git add README.md

git commit -m "First Commit"

git remote add origin https://github.com/indradhanush/Open-Source-Intro.git

git push -u origin master

