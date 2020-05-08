# Gary140420

## Build
`ng build --prod`
npm i -g lite-server
cd myapp\dist\myapp\ 
lite-server // this runs the application
## Deployment on github
git init
git add .
git commit -m "first commit"
git remote add origin https://github.com/perlov3301/gary140420.git
git push -u origin master

`add file to github`:
git add .
git commit -m "Adding existing file"
git remote add origin https://github.com/perlov3301/gary140420.git
git push origin ..your-branch..
or 
git push -u origin master

## this works
git add -A
git commit -m "comment"
git remote add my1  https://github.com/perlov3301/deploygary140420.git
git push -u my1  HEAD:master
reload your repository on github
### see:https://stackoverflow.com/questions/48349103/update-my-repository-on-github
### answer of user1561783
### and git pull https://github.com/perlov3301/deploydist1 master  --allow-unrelated-histories

