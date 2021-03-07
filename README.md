# First Contributions

This project aims to simplify and guide the way beginners make their first contribution. If you are looking to make your first contribution, follow the steps below.

If you don't have git on your machine install it from [here](https://git-scm.com/downloads).

## 📌Fork this repository
Click on fork button at the top right corner. This will create a copy of this repository in your account.

## 📌Clone this repository
Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository hit the clone button on your forked repo and copy the link.

On your terminal, run the following git command:
  ```
  git clone "link you just copied"
  ```
Change to the repository directory on your computer (if you are not already there):
  ```
  cd first-contributions
  ```
## 📌Create a branch
Now create a branch using the `git checkout` command:
  ```
  git checkout -b your-new-branch-name
  ```
 
## 📌Make necessary changes and commit those changes
* Now open `Contributors.md` file on your text editor and on a new line add 
  ```
  * (your name)[Link to your github profile] 
  ```
  and save the file.
* Type 
  ```
  git status
  ``` 
  on your terminal and you’ll see that there is a modified file – Contributors.md
* Afterward on your terminal type 
  ```
  git add .
  ```
  This command will stage all the changes that you have made in Contributors.md file.
* Then on the terminal type 
  ```git commit -m “type a message" 
  ```
  (Example “added my name to contributors.md file”).
  
## 📌 Push changes to GitHub
Now push your changes to GitHub
  ```
  git push origin <add-your-branch-name>
  ```
  
## 📌 Create a Pull Request
* Go back to your repo.
* Hit “new pull request” and compare between forks.
* Confirm the pull request.
* Soon we'll merge your pull request into the master branch of this project. You will get a notification email once the changes have been merged.

**Congratulations on creating your first pull request. Happy Open Sourcing!**
