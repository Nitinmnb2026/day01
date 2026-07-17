
   DAy 01 practice
   
   
   18  git init
   19  ls -al
   20  clear
   21  git status
   22  clear
   23  echo "Hi i am nitin ranjan" > details.txt
   24  git status
   25  git add details.txt
   26  git status
   27  git commit -m "Chore: initialization of code"
   28  clear
   29  git log
   30  git log --oneline
   31  echo " i am learning Git" > details.txt
   32  git status
   33  git add details.txt
   34  git commit -m "feat : add details"
   35  git log --oneline
   36  clear
   37  cat details.txt
   38  git log --oneline
   39  echo "login details " >log.txt
   40  git commit -m "feat : login details"
   41  git add log.txt
   42  git commit -m "feat : login details"
   43  git log --oneline
   44  ls
   45  clear
   46  git reflog
   47  vim .gitignore
   48  ls
   49  ls -al
   50  clear
   51  touch new.log
   52  ls
   53  git status
   54  git add .gitignore
   55  git status
   56  echo "new logs created" > new.log
   57  git status
   58  clear
   59  git branch
   60  git checkout -b feat/login
   61  ls
   62  git log --oneline
   63  echo "New footer on login page added " > footer.txt
   64  ls
   65  git add .
   66  git commit - m "feat: login footer added"
   67  git commit -m "feat: login footer added"
   68  clear
   69  git reflog
   70  git checkout -b master
   71  git checkout  master
   72  ls
   73  git merge feat/login
   74  git log --oneline
   75  ls
   76  clear
   77  git branch
   78  git branch -d feat/login
   79  git branch
   80  ls
   81  clear
   82  git checkout -b bugfix/typo
   83  ls
   84  vim footer.txt
   85  git checkout master
   86  vim footer.txt
   87  git status
   88  cat footer.txt
   89  git checkout  bugfix/typo
   90  cat footer.txt
   91  clear
   92  git commit -am "Bugfix: background green"
   93  git log --oneline
   94  git checkout master
   95  cat footer.txt
   96  git log --oneline
   97  vim footer.txt
   98  git commit -am "feat:background red"
   99  git merge bugfix/typo
  100  git merge bugfix/typo
  101  git status
  102  git commit -m "Merge:resolved"
  103  git merge bugfix/typo
  104  git status
  105  git log --oneline
  106  clear
  107  git log --oneline
  108  git reflog
  109  git log --oneline --graph
  110  clear
  111  git log --oneline --graph
  112  git branch -d bugfix/typo
  113  git log --oneline --graph
  114  clear
  115  git log --oneline
  116  git reset 546cbf6
  117  git status
  118  git log --oneline
  119  cat footer.txt
  120  clear
  121  vim footer.txt
  122  git status
  123  git add .
  124  git status
  125  git commit -m "Reset: new feat"
  126  git log --oneline
  127  git revert 04ef082
  128  git status
  129  git show 04ef082
  130  clear
  131  git status
  132  ls
  133  git add .
  134  git status
  135  git commit -m "revert"
  136  git log --oneline
  137  clear

