Commands Basics
========

Help commands
--------

Man page

:code:`$ man <command>`

Whatis 

:code:`$ whatis <command>`

Option –h 

:code:`$ <command> -h`


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

Check recent commands

:code:`$ history <env_var>`


Directory change
--------

Check current directory
:code:`$ pwd`

Go to home directory

:code:`$ cd ~`

Go to previous directory

:code:`$ cd -`

Go to parent directory

:code:`$ cd ..`
