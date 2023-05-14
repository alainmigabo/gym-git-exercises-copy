# Gym Git Exercise Solutions

## Bundle 1

### Exercise 1

My terminal commands with their outcomes are:

alain@alain-HP-ProBook-440-G4:~/Desktop/Alain/gym/git-exercises$ git init
Initialized empty Git repository in /home/alain/Desktop/Alain/gym/git-exercises/.git/
alain@alain-HP-ProBook-440-G4:~/Desktop/Alain/gym/git-exercises$ git add . 
alain@alain-HP-ProBook-440-G4:~/Desktop/Alain/gym/git-exercises$ git commit -m "initial commit"
[main (root-commit) 2e07fe1] initial commit
 2 files changed, 13 insertions(+)
 create mode 100644 README.md
 create mode 100644 index.html
alain@alain-HP-ProBook-440-G4:~/Desktop/Alain/gym/git-exercises$ git branch -M main
alain@alain-HP-ProBook-440-G4:~/Desktop/Alain/gym/git-exercises$ git push origin main
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
alain@alain-HP-ProBook-440-G4:~/Desktop/Alain/gym/git-exercises$ git remote add origin https://github.com/alainmigabo/Gym-Git-Exercise-Solutions.git
alain@alain-HP-ProBook-440-G4:~/Desktop/Alain/gym/git-exercises$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 476 bytes | 238.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/alainmigabo/Gym-Git-Exercise-Solutions.git
 * [new branch]      main -> main
alain@alain-HP-ProBook-440-G4:~/Desktop/Alain/gym/git-exercises$ git add . 
alain@alain-HP-ProBook-440-G4:~/Desktop/Alain/gym/git-exercises$ git push origin main
Everything up-to-date
alain@alain-HP-ProBook-440-G4:~/Desktop/Alain/gym/git-exercises$ git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md
        modified:   index.html
        new file:   styles.css

alain@alain-HP-ProBook-440-G4:~/Desktop/Alain/gym/git-exercises$ git add . 
alain@alain-HP-ProBook-440-G4:~/Desktop/Alain/gym/git-exercises$ git commit -m "a little change on the readme file"
[main 7a81dc7] a little change on the readme file
 3 files changed, 6 insertions(+), 2 deletions(-)
 create mode 100644 styles.css
alain@alain-HP-ProBook-440-G4:~/Desktop/Alain/gym/git-exercises$ git push origin main
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (5/5), 509 bytes | 254.00 KiB/s, done.
Total 5 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/alainmigabo/Gym-Git-Exercise-Solutions.git
   2e07fe1..7a81dc7  main -> main
alain@alain-HP-ProBook-440-G4:~/Desktop/Alain/gym/git-exercises$ git add . 
alain@alain-HP-ProBook-440-G4:~/Desktop/Alain/gym/git-exercises$ git commit -m "a little change on the readme file"
[main 6d70142] a little change on the readme file
 1 file changed, 1 insertion(+), 1 deletion(-)
alain@alain-HP-ProBook-440-G4:~/Desktop/Alain/gym/git-exercises$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 354 bytes | 177.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/alainmigabo/Gym-Git-Exercise-Solutions.git
   7a81dc7..6d70142  main -> main
alain@alain-HP-ProBook-440-G4:~/Desktop/Alain/gym/git-exercises$ git add . 
alain@alain-HP-ProBook-440-G4:~/Desktop/Alain/gym/git-exercises$ git commit -m "a little change on the readme file"
[main af5aabf] a little change on the readme file
 1 file changed, 1 insertion(+), 1 deletion(-)
alain@alain-HP-ProBook-440-G4:~/Desktop/Alain/gym/git-exercises$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 352 bytes | 176.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/alainmigabo/Gym-Git-Exercise-Solutions.git
   6d70142..af5aabf  main -> main
alain@alain-HP-ProBook-440-G4:~/Desktop/Alain/gym/git-exercises$ git branch
* main
alain@alain-HP-ProBook-440-G4:~/Desktop/Alain/gym/git-exercises$ git checkout -b dev
Switched to a new branch 'dev'
alain@alain-HP-ProBook-440-G4:~/Desktop/Alain/gym/git-exercises$ git checkout -b test
Switched to a new branch 'test'
alain@alain-HP-ProBook-440-G4:~/Desktop/Alain/gym/git-exercises$ git branch
  dev
  main
* test
alain@alain-HP-ProBook-440-G4:~/Desktop/Alain/gym/git-exercises$ git checkout dev
M       README.md
Switched to branch 'dev'
alain@alain-HP-ProBook-440-G4:~/Desktop/Alain/gym/git-exercises$ git branch
* dev
  main
  test
alain@alain-HP-ProBook-440-G4:~/Desktop/Alain/gym/git-exercises$ git branch -d test
Deleted branch test (was af5aabf).
alain@alain-HP-ProBook-440-G4:~/Desktop/Alain/gym/git-exercises$ git branch
* dev
  main
