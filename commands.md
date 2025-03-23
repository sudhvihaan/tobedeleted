git config --global user.name "Sudhakar"
git config --global user.email m.k.sudhakar@gmail.com
git init
git branch -M main 
git remote add origin git@github.com:sudhvihaan/tobedeleted.git
git push -u origin main 

Note : file by defauld (workspace) - git add (Index/staging) - git commit (Local Repo)

Second - comment 


git diff --staged
git branch
git log --oneline  ///afer the merge


git branch feature1
git switch feature1
git branch # you will see the head sitting at feature1

git ls-tree --name-only HEAD /// to see what is tracked in my main brach

git log --oneline --all
PS C:\Sudhakar\Learn\0001-AWS\01-Master-VPC-UdemyRef\VPC-Automated\vpc\0001_GItHUB_Mastering\chap2> git log --oneline --all
WARNING: terminal is not fully functional
Press RETURN to continue 
107d979 (HEAD -> main, origin/main, origin/feature1, feature1) added commands and py file to feature1
What it tells you:
You're on the commit 107d979
HEAD is pointing to main → you're on the main branch
Both origin/main and origin/feature1 are also pointing here (so they’re up to date)
Local feature1 also points to this commit — so it's merged into main