# Foundation course

- [Git, GitHub, & GitHub Desktop for beginners](https://www.youtube.com/watch?v=8Dd7KRpKeaE)

- [The Odin project](https://www.theodinproject.com/paths/foundations/courses/foundations)

# Learn Git and Github

Learn complete Git and Github

## Installation of git

[GIT](https://git-scm.com/downloads)

- Once the git is install go to your terminal
- git --version
- make sure the git is installed correctly

## Next step - set your config file by setting your name and email

- [Article](https://www.theserverside.com/blog/Coffee-Talk-Java-News-Stories-and-Opinions/The-global-Git-config-files-key-settings-and-usages#:~:text=How%20to%20do%20a%20git,It's%20that%20easy.) - Git Config

```
Set your username:

 git config --global user.name "Robert Welker"

Set your email address:

git config --global user.email "robert123@gmail.com"

Note: your directly also change the config file using below command

git config --global edit


```

## Let's create project now and practice the git command

- create new folder
- switch to new folder
- git init ( initialize the folder for git repository)
- create some file, script.js, index.html, style.css add some code

## commands to add

- git add filename
  or
- git add . // adds all the changes
- git status // to check the status
- git commit -m "initial commit" to commit the change to git resporistary. add the resonable message about the file and changes

- git log // to check how may commit done previously

- git status // to check the status of the file

## how to create branch and switch to different branch

- git branch // first u will see the master branch if there is no any branch crearted previoulsy.
- git log

- git checkout -b feature-branch // create new feature-branch and switch to the new branch

create different feature branches as you progress in your project. commit regularly.

![git-branch](/image/github-flow.jpg)
