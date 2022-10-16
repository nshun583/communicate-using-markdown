# header1
## header2
### header3
#### header4
##### header5
###### header6
![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

code example
```
# .bash_profile

# Get the aliases and functions
if [ -f ~/.bashrc ]; then
	. ~/.bashrc
fi

# User specific environment and startup programs

# for git
. ~/git-completion.bash
. ~/git-prompt.sh
GIT_PS1_SHOWDIRTYSTATE=1
GIT_PS1_SHOWUPSTREAM=1
GIT_PS1_SHOWUNTRACKEDFILES=
GIT_PS1_SHOWSTASHSTATE=1
export PS1='[\[\033[1;32m\]\u@\h\[\033[00m\] \[\033[1;37m\]\w\[\033[1;31m\]$(__git_ps1)\[\033[00m\]]\$ '

# ssh-agent auto startup
eval `ssh-agent` > /dev/null 2>&1
eval `ssh-add ~/.ssh/id_ed25519 > /dev/null 2>&1`
```
