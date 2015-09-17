git commit -m '0'

git checkout -b bug-fix
git commit -am '3'
git commit -am '4'

git pull origin master
//Had to resolve conflicts here
git commit -am "5" //For the merge
git push --all
git commit -am "6"
git pull origin bug-fix-experimental
git commit -am "11"
git push origin bug-fix
 
git pull origin app
git commit -m '1'
git commit -m '2'

git commit -m '7'
git commit -m '8'
git commit -m '9'
