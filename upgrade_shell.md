# Modify Reverse Shells
`python3 -c 'import pty; pty.spawn("/bin/bash")'`

ctrl-z

`stty raw -echo; fg`

enter

`export TERM=xterm-256color`
