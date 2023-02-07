# Foundation course

- video Link [Git & GitHub](https://www.youtube.com/watch?v=hrTQipWp6co){:target="\_blank"}

- video Link [Git, GitHub, & GitHub Desktop for beginners](https://www.youtube.com/watch?v=8Dd7KRpKeaE){:target="\_blank"}

- Article [The Odin project](https://www.theodinproject.com/paths/foundations/courses/foundations){:target="\_blank"}

# Learn Git and Github

Learn complete Git and Github

## Installation of git

[GIT](https://git-scm.com/downloads){:target="\_blank"}

- Once the git is install go to your terminal
- git --version
- make sure the git is installed correctly

## Next step - set your config file by setting your name and email

- [Article Git config](https://www.theserverside.com/blog/Coffee-Talk-Java-News-Stories-and-Opinions/The-global-Git-config-files-key-settings-and-usages#:~:text=How%20to%20do%20a%20git,It's%20that%20easy.){:target="\_blank"}

```
Set your username:

 git config --global user.name "Robert Welker"

Set your email address:

git config --global user.email "robert123@gmail.com"

Now u can check the status of you usename and email

git config --list

Note: your directly also change the config file using below command


git config --global edit


```

## Let's create project now and practice the git command

- create new folder
- switch to new folder
- git init ( initialize the folder for git repository)
- create some file, script.js, index.html, style.css add some code

## commands to add

- (git add) filename
  or
- (git add .) // adds all the changes
- (git status) // to check the status
- (git commit -m "initial commit") to commit the change to git resporistary. add the resonable message about the file and changes

- (git log) // to check how may commit done previously

- to create branch
- (git branch feature)

- To switch to branch
- (git checkout feature)

or

- you can use single command to crete branch and switch to the branch

  - (git checkout -b feature2)

- switch to parent branch and use below command to merge the feature branch
- (git merge feature2)

## how to create branch and switch to different branch

- git branch // first u will see the master branch if there is no any branch crearted previoulsy.
- git log

- git checkout -b feature-branch // create new feature-branch and switch to the new branch

create different feature branches as you progress in your project. commit regularly.

![git-branch](/image/github-flow.jpg)

# Generating SSh key

[Document](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account?tool=webui){:target="\_blank"}

### command to generate SSH key

- open your Window PoweSheel as administrator
- use your github email id

- ssh-keygen -t ed25519 -C "your_email@example.com"

- to copy the SSH key

- cat ~/.ssh/id_ed25519.pub | clip

- go to github setting SSH and GPG keys
- Click new SSH key
- give title
- paste the key in box
- click on add SSH button
