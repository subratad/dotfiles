# .bashrc

# Source global definitions
if [ -f /etc/bashrc ]; then
	. /etc/bashrc
fi

# Uncomment the following line if you don't like systemctl's auto-paging feature:
# export SYSTEMD_PAGER=

# User specific aliases and functions

#############################
### ENVIRONMENT VARIABLES ###
#############################

PS1="\n\[\033[0;31m\][\u@\H:\033[0;32m \$PWD]\n$\[\e[0m\] "

###############
### ALIASES ###
###############

alias ll="ls -altr --color=auto"
alias u="cd ../"
alias b="cd -"
alias q="exit"
alias install="sudo dnf -y install"
alias remove="sudo dnf remove"
alias update="sudo dnf -y clean all; sudo dnf -y update"
alias upgrade="sudo dnf -y clean all; sudo dnf -y upgrade"
alias autoremove="sudo dnf -y autoremove"
alias search="sudo dnf search"
alias tmux="tmux -2"


[[ $TERM = "xterm-256color" ]] && { tmux && exit 0; }
