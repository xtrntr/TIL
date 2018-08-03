## .bash_profile vs .bashrc
.bash_profile is executed for login shells, .bashrc is executed for interactive non-login shells
You can check if your Bash shell is started as a login-shell by running: `shopt login_shell`

tmux interaction
on Mac OS X opening a new pane runs bash_profile
SSH login to Ubuntu (AWS) also runs bash_profile
