# elite-keybinds
Shared Keybinds for Elite Dangerous
## installation
- Install Git Bash for Windows
- Get a Github account
- Visit https://github.com/delboy1978uk/elite-keybinds
- Click the `Fork` button at the top right
- Copy the github URL of your forked repository
- Browse to a folder where you can clone this repository
- Right click, select 'Git Bash from here'
- type the following:
```
git clone https://github.com/[YOUR_USER_NAME_HERE]/elite-keybinds
```
- Copy the binds file in the `elite-keybinds` folder to your Elite Dangerous key bindings folder
## contributing
If you have made changes to the config file and wish to merge it in to the master branch, do the following.
- Copy the binds file from the Elite Dangerous folder to the cloned repository in `elite-keybinds`, overwriting the original
- In that folder, right click, select `Git Bash here`
- you can see the files that changed by typing `git status`
- you can see the actual changes with `git diff`
- add the changes 
```
git add .
git commit -a
```
- At this point, a text editor called nano opens. Type in what you changed. e.g.
```
Added key bindings for scan bad guys cargo button
```
- press CTRL-O, then RETURN (writes changes)
- press CTRL-X (exit text editor)
Your changes are ready to push to Github
```
git push
```
Note that this has only updated your own branch on Github, and not the master branch at  https://github.com/delboy1978uk/elite-keybinds

The final stage is to copy paste the pull request link that you saw appear when you typed `git push`. Browse there, and open the pull request. I'll get notified, and if all is well I will merge in the changes!
