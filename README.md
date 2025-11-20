    1  git --version
    2  mkdir Busurin2011
    3  cd Busurin2011
    4  git init
    5  git remote add origin git@github.com:9074186/Busurin2011.git
    6  echo "commit 1" > file.txt
    7  git add .
    8  git commit -m "1 commit"
    9  echo "commit 2" >> file.txt
   10  git commit -m "2 commit"
   11  echo "commit 3" >> file.txt
   12  git commit -m "3 commit"
   13  git commit -am "2 commit"
   14  git commit -am "3 commit"
   15  mkdir Busurin2011
   16  cd Busurin2011
   17  git init
   18  git remote add origin git@github.com:9074186/Busurin2011.git
   19  echo "commit 1" > file.txt
   20  git add .
   21  git commit -m "1 commit"
   22  echo "commit 2" >> file.txt
   23  git commit -am "2 commit"
   24  echo "commit 3" >> file.txt
   25  git commit -am "3 commit"
   26  echo "commit 4" >> file.txt
   27  git commit -am "4 commit"
   28  git push -u origin main
   29  [200~error: failed to push some refs to 'github.com:9074186/Busurin2011.git'
   30  git remote add origin git@github.com:9074186/Busurin2011.git
   31  git remote -v
   32  git push -u origin main
   33  git remote add origin git@github.com:9074186/Busurin2011.git
   34  git branch -M main
   35  git push -u origin main
   36  git log --oneline
   37  git checkout -b dev 1f961b5
   38  push -u origin dev
   39  git push -u origin dev
   40  git checkout -b test 1f961b5
   41  git push -u origin test
   42  git add capybara.svg
   43  git commit -m "add capybara.svg"
   44  xed capybara.svg
   45  git commit -am "change capybara color"
   46  xed capybara.svg
   47  cd Busurin 2011
   48  git push
   49  xed capybara.svg
   50  git commit -am "change background color"
   51  git push
   52  git checkout test
   53  git log main --oneline
   54  git cherry-pick 1f961b5
   55  git cherry-pick --skip
   56  git cherry-pick 749f86d
   57  xed file.txt
   58  git add file.txt
   59  git cherry-pick --continue
   60  git cherry-pick 859e18d
   61  xed file.txt
   62  git cherry-pick --continue
   63  git add file.txt
   64  git cherry-pick --continue
   65  git push
   66  git checkout main
   67  git merge test -m "merge test"
   68  git status
   69  git add file.txt
   70  git commit -m "save changes"
   71  git checkout main
   72  git merge test -m "merge test"
   73  xed file.txt
   74  git add file.txt
   75  git -m commit "conflict"
   76  git -am commit "changes"
   77  git commit -m "changes"
   78  git checkout main
   79  git merge test -m "merge test"
   80  git push
   81  git checkout dev
   82  git rebase main
   83  git push --force
   84  history > README.md
