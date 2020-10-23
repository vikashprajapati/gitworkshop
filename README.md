# Git Workshop

### INSTALL GIT

Github provides desktop clients that include a graphical user interface for the most common repository actions and an automatically updating command line edition of Git for advanced scenarios.

### Github for Windows

https://windows.github.com

###Github for Mac

https://mac.github.com



### Create a local repository

First open the folder or create a folder where you want to initialize your
repository.
After opening the folder type the below command in your terminal (terminal
must be in your current directory where new repository has to be initialized)

```
git init
```

### Download a project and its entire version history

```
git clone[url]
```
### Add files to staging area

To add files to the staging area type the command below, filename will be the file which you want to add.

```
git add filename
```
To add all files to the staging area which you have changed, use the command as shown below.

```
git add .
```
### Commit changes to local repository
To commit the new changes we use commit command along with a new message which tells what changes or features were done.
```
git commit -m "commit message"
```
### Upload all local branch commits on Github

```
git push [alias][master]
```
### Combine specified branch's history into current branch
```
git merge [branch]
```
### Download bookmark history and incorporate changes
```
git pull
```
