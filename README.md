# linux privilege acceleration | phishing

A simple sudo - phishing program that allows you to steal the root user password.

# Usage:
first of all, make sure the _sudo_ file is an executable.
if not, run the following command to your terminal

```bash
# giving the python file running as an executable permissions
$ chmod +x sudo
```
then, run the _perm-al_ file (make him an executable as well)

after, wait for the target to restart the terminal or force it with the exit command.
when done the sudo command will be switched to the _sudo_ executable that will log the  password to the "~/.cache/pass.gv" file

# Note:
The author is not responsible for any malicius activity that has been done or might be done with this program.
Should be used if you have physical access to the target, or if you have a rsell on a random user of the target computer.
