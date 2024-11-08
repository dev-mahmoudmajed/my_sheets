# git cheat Sheet

| Command |what command Do|
| ----------- | ----------- |
|`git status`||
|`git clone [link]`|Take clone from Repo To your Local|
|`git add [file or folder name]`|move it to staging Area|
|`git add *`|move all files and folder To staging Area|
|`git reset head [file or folder name]`|un stage|
|`git commit`|move it to local and make it ready to push mean to upload|
|` git commit -am "Add and commit all"`|make add all and commit for all changes you make it|
|`git branch`|tell me any branch i work on it|
|`git remote -v`|tell me the remote Repo Name|
|`git push`|upload == update Remote Repo|
|`git push [Remote Name] [Repo Name]`|upload == update Remote Repo|
|`git push [master] [origin]`|upload == update Remote Repo|
|`git pull [Remote Repo name] = git fetch + git merge`|Take changes from remote and update yours|

|Configuration Command |what command Do|
| ----------- | ----------- |
|`git help config`|show you all configuration commands|
|`git config --global user.email`|Tell me = get  The email of global user|
|`git config --global user.email "email"`|Set The email of global user|
|`git config --global user.name`|Tell me = get  The name of global user|
|`git config --global user.name "Name"`|Set The name of global user|
|`git config -l`|show me all config List|
|`git config -l --show-origin`|show me where the get take the configuration|
|`Q`|if work with cmder to exit it|
|`git config --global --unset user.name`|remove user name from configuration|
|`git config --global --edit`|Open my editor to change configuration setting you can change color and other thing|

## Make Public key

|Make Public key Command |what command Do|
| ----------- | ----------- |
|`ssh-keygen -t rsa -b 4096 -C "email"`||
|`cat ~/.ssh/id_rsa.pub`||
|`ssh -T git@github.com`||

## init Project

| Command |what command Do|
| ----------- | ----------- |
|`git init`|to make this project git repo and track changes|
|``||
|``||
|``||
|``||
|``||
|``||
|``||
|``||
|``||
|``||

## Project To GitHub

|Command |what command Do|
| ----------- | ----------- |
|`touch .gitignore`|ignore files and holder write inside it `*.log` => any file have this extend will ignore  second `!.vip` this file will not ignore or `folderName` will ignore it|
|`git add -f [filename]`|will add if it ignore|
|`git remote add origin git@github.com:MahmoudMajedMahmoudAlsheikh/git_crash_course.git`||
|`git push origin main`|make push|
|`git push -u origin main`|make pull first and second push|
|``||
|``||
|``||
|``||
|``||
|``||
