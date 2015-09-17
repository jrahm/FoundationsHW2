git commit -m '0'

git checkout -b bug-fix
git commit -am '3'
git commit -am '4'

git pull origin master
//Had to resolve conflicts here
git commit -am "5" //For the merge
git push --all
git commit -am "6"
 
git pull origin app
git commit -m '1'
git commit -m '2'
