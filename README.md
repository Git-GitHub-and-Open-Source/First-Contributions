# First Contributions

* Install git from [here](https://git-scm.com/downloads).
* Click on fork button at the top right corner. This will create a copy of this repository in your account.
* Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository hit the clone button on your forked repo and copy the link.
* On your terminal, type
  ```
  git clone (link)
  ```
* Change to the repository directory on your computer (if you are not already there):
  ```
  cd first-contributions
  ```
* Now create a branch using the `git checkout` command:
  ```
  git checkout -b your-new-branch-name
  ```
* Now add Contributors.md file on your text editor and on a new line add 
  ```
  * (your name) 
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
* Now push the commit
  ```
  git push origin <add-your-branch-name>
  ```
* Go back to your repo.
* Hit “new pull request” and compare between forks.
* Confirm the pull request.
* Soon we'll merge your pull request into the master branch of this project. You will get a notification email once the changes have been merged.

**Congratulations on creating your first pull request. Happy coding**
