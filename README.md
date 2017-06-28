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
$ sudo chown root:root /usr/local/bin/*
```
Go to the git working folder and...
```sh
$ mkrepo
```

### How it works
```sh
################################################################################

 Your GIT username is zsoltibaba37.

################################################################################
 The name of the current directory will be the name of the repository.
 The repository name is setting up for temp.
 Please write in the first commit: 1234
 Creating a README.md file.
 Down
################################################################################
 Create an empty Git repository.
Initialized empty Git repository in /home/username/temp/.git/
 Down
################################################################################
 Add all files.
 Down
################################################################################
 Record changes to the repository.
[master (root-commit) c540882] 1234
 1 file changed, 1 insertion(+)
 create mode 100644 README.md
 Down
################################################################################
Enter host password for user 'zsoltibaba37':
 Adds a remote named <name> for the repository at <url>.
 Down
################################################################################
 Push all file to the repository, and set upstream.
Enter passphrase for key '/home/username/.ssh/id_rsa':
Counting objects: 3, done.
Writing objects: 100% (3/3), 214 bytes | 0 bytes/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To github.com:zsoltibaba37/temp.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.
 Down
################################################################################
 And finally let see the status of the repository.
On branch master
Your branch is up-to-date with 'origin/master'.
nothing to commit, working tree clean
################################################################################
 The temp repository has been completed.
 Bye Bye. And have a nice day.
################################################################################
```
2017-06-27
