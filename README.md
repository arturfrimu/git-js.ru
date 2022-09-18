#Git configuration

![alt text](https://github.com/arturfrimu/git/blob/master/src/main/resources/images/configuration/git.jpg?raw=true)

###Initialize a git repository locally

```
git init
```

###Terminal configuration

```
zsh: oh-my-zsh (sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)")
bash: git-bash-prompt
powershell: posh-git
```

###Config credentials

```
git config user.name "Josh Doe"
git config user.email "john.doe@gmail.com"

Flags:
--local:
--global:
--system
``` 

###Show what file or folder contains

```
cat .git/config
```

###Show configurations in current directory

```
git config --list
```

###Show global configurations

```
git config --list --global
```

###Show more commands

```
git config --global -h
```

###Info about specific command

```
git help command-name
```

###Unset configurations

```
git config --unset user.name
git config --unset user.email
git config --remove-section user
```
###Setup core editor

```
git config --global core.editor
```

##Alias
###Add alias for commands

```
git config --global alias.alias-name 'command-name -flag'
git config --global alias.c 'config --global'
```

###Combine multiple commands

```
git config --global alias.c '!git ...; git ...'
```

###Add file to index

```
git add file-name
git add file1 file2 file3
```

###Add file to repository

```
git commit -m "commit message"
```

##Show

###Show last commit
```
git show
git show --pretty=fuller
```

###Show commit by id
```
git show commit-id
```