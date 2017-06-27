# mkrepo mean make repository

This script create a new github repository under command line. 

And then push all file to the repository.

The repository name is same as the current directory name.


#### Installation

You do not have to install it.

#### Files

mkrepo

#### How to execute the script

First time I copy the file to the bin folder. 
```sh
$ chmod +x mkrepo
$ sudo cp -p mkrepo /usr/local/bin
```
Go to the git working folder and...
```sh
$ mkrepo
```

### How it works
```sh
$ The repository name is "pwd | xargs basename" . 
$ Give me the first commit: 
$ Enter host password for user '<git username>'
$ Enter passphrase for key '/home/<user>/.ssh/id_rsa':
```
2017-06-27
