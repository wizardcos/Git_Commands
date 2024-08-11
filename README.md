<h1 align = "center" ; color = "blue" >Git Commands For the beginner</h1>

## 🛠 Cloning Repo or adding remote repo 

1. For initilization a git repo

   ```sh
   git init
   ```
1. For Cloning an exsisting repo in local

   ```sh
   git clone <url>
   ```

2. For adding a remote repo 

   ```sh
   git remote add origin <url>
   ```

3. now for selecting file's that you want to keep the track of changing 

   ```sh
   git add <file name>
   ## for selecting  all files
   git add . 
   ```

4. For the commit in the repo 

   ```sh
   git commit -m " your message"
   ```

5. for both at the same time selecting  and commit 

   ```sh
   git commit  -am " your message "
   ```

6. For pushing code on github repo

   ```sh
   git push 
   ```


7. For puling updated code from the repo

   ```sh
   git pull <url>
   ```
## 🛠 For commits Related
8. For checking the history of the commits that made

   ```sh
   git log
   ```

9. For Resting the commit that are made

   ```sh
   git reset hard < commit code >
   ## for code mean when you will run command git log each commit will have a code thats the code you have to insert
   ```

10. For Checking status 

   ```sh
   git status
   ```

## 🚀 Branch Related

11. For creating a new branch

   ```sh
   git branch < neww branch name you want to have>
   ```

12. for checking the current branch you are on

   ```sh
   git branch
   ```

13. For going into another branch

   ```sh
   git checkout <branch name you want to enter>
   ```

14. for merging code from the new branch to main branch 

   ```sh
   git merge <branch you want to merge>
   ```
15. for creating a new branch & moving into that branch 

   ```sh
   git checkout -b <name>
   ```
## 🚀 Deleting 
16. Delete a local branch

   ```sh
   git branch -d <branch-name>
   ```
17. Delete a remote branch.

   ```sh
   git push origin --delete <branch-name>
   ```
## 🚀  Configuration
18. Set your name in Git (global configuration).

   ```sh
   git config --global user.name "Your Name"
   ```
19. Set your email in Git (global configuration).

   ```sh
   git config --global user.email "you@example.com"
   ```
## 🚀  Help
20.  Get help for a specific Git command.

   ```sh
   git help <command>
   ```
 <h3 align ="center" >For any inquiries Email me</h3>
