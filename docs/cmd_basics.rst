Commands Basics
========

Help commands
--------

:code:`$ man <command>`     # man page

:code:`$ whatis <command>`  # whatis 

:code:`$ <command> -h`      # option -h


Environment variables
--------

Create variable in shell

:code:`$ <env_var>="var_value"`
:code:`$ export <env_var>`

Define vairable in bash configuration file

:code:`export <env_var>="var_value"` # add the setting to ~/.bashrc

:code:`source ~/.bashrc`             # load new environment variables to shell

Print variable

:code:`$ echo $<env_var>`
:code:`$ printenv <env_var>`


History commands
--------

:code:`$ history`                   # check recent commands

:code:`$ history | grep <string>`  # find previous command with specific string


Directory change
--------

:code:`$ pwd`   # check current directory

:code:`$ cd ~`  # go to home directory

:code:`$ cd -`  # go to previous directory

:code:`$ cd ..` # go to parent directory


Download from the internet
--------

:code:`$ wget <url>` 

:code:`$ curl <url>` 