# TTY-Shell
Here are some commands which will allow you to spawn a tty shell. Obviously some of this will depend on the system environment and installed packages.
# match the target system
## Python & Python3
`python -c 'import pty; pty.spawn("/bin/bash")'`
`python -c 'import pty; pty.spawn("/bin/sh")'`
`python3 -c 'import pty; pty.spawn("/bin/bash")'`
`python3 -c 'import pty; pty.spawn("/bin/sh")'`
## Bash
`echo os.system('/bin/bash')`
`/bin/sh -i`
## Perl
`perl —e 'exec "/bin/sh";'`
`perl: exec "/bin/sh";`
## Ruby 
`ruby: exec "/bin/sh"`
