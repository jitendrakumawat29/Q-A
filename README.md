Git rebase
git branch --show-current
Feature rebased with master

git fetch
git checkout master
git pull
git checkout feature/add-to-cart 
git rebase master                              
git status
git push -f



Ticket branch rebased with feature branch

git checkout CHKPAY-1750/jkumar
git rebase origin/feature/add-to-cart
git status
git push or git push -f



Remove conflicts 

git checkout master
git pull 
git checkout CHKPAY1533/jkumar
git rebase master
git status

After removing conflits 
git rebase --continue
git status
git add .
Then :wq then enter
git push -f
