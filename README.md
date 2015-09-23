# workuser@ubuntu_all:~$ ssh -T git@github.com
The authenticity of host 'github.com (192.30.252.129)' can't be established.
RSA key fingerprint is 16:27:ac:a5:76:28:2d:36:63:1b:56:4d:eb:df:a6:48.
Are you sure you want to continue connecting (yes/no)? y
Please type 'yes' or 'no': yes
Warning: Permanently added 'github.com,192.30.252.129' (RSA) to the list of known hosts.
Hi dengshiqiong! You've successfully authenticated, but GitHub does not provide shell access.
user@ubuntu_all:~$ /mnt/hgfs/SourceCode
bash: /mnt/hgfs/SourceCode: No such file or directory
user@ubuntu_all:~$ /mnt/hgfs/SourceCode$ git clone git@github.com:dengshiqiong/work.git
bash: /mnt/hgfs/SourceCode$: No such file or directory
user@ubuntu_all:~$ cd /mnt/hgfs/SourceCode
bash: cd: /mnt/hgfs/SourceCode: No such file or directory
user@ubuntu_all:~$ cd /mnt/hgfs/SourceCode/
bash: cd: /mnt/hgfs/SourceCode/: No such file or directory
user@ubuntu_all:~$ cd /mnt/hgfs/D/SourceCode
user@ubuntu_all:/mnt/hgfs/D/SourceCode$ git clone git@github.com:dengshiqiong/work.git
Cloning into 'work'...
Warning: Permanently added the RSA host key for IP address '192.30.252.128' to the list of known hosts.
warning: You appear to have cloned an empty repository.
user@ubuntu_all:/mnt/hgfs/D/SourceCode$ 
user@ubuntu_all:/mnt/hgfs/D/SourceCode$ git config --global commit.template ~/.gitmessage
user@ubuntu_all:/mnt/hgfs/D/SourceCode$ cd
user@ubuntu_all:~$ git config --global commit.template ~/.gitmessage
user@ubuntu_all:~$ git config --global commit.template ~/.gitmessage
user@ubuntu_all:~$ git config --global user.name "dengshiqiong"
user@ubuntu_all:~$ git config --global user.email"dengshiqiong@cvte.com"
user@ubuntu_all:~$ git config --global core.editor"vim"
user@ubuntu_all:~$ git config --global color.ui"auto"
user@ubuntu_all:~$ git config config
error: key does not contain a section: config
user@ubuntu_all:~$ git config --list
commit.template=/home/user/.gitmessage
user.name=dengshiqiong
user@ubuntu_all:~$ cd ~/.gitmessage
bash: cd: /home/user/.gitmessage: No such file or directory
user@ubuntu_all:~$ git config --global user.email "dengshiqiong@cvte.com"
user@ubuntu_all:~$ git config --global core.editor "vim"
user@ubuntu_all:~$ git config --global core.editor "vim"
user@ubuntu_all:~$ 
user@ubuntu_all:~$ git config --global color.ui "auto"
user@ubuntu_all:~$ git config --list
commit.template=/home/user/.gitmessage
user.name=dengshiqiong
user.email=dengshiqiong@cvte.com
core.editor=vim
color.ui=auto
user@ubuntu_all:~$ git config <key>
bash: syntax error near unexpected token `newline'
user@ubuntu_all:~$ cd /mnt/hgfs/D/work
bash: cd: /mnt/hgfs/D/work: No such file or directory
user@ubuntu_all:~$ cd /mnt/hgfs/D/work/
bash: cd: /mnt/hgfs/D/work/: No such file or directory
user@ubuntu_all:~$ cd /mnt/hgfs/D/SourceCode
user@ubuntu_all:/mnt/hgfs/D/SourceCode$ git init
Initialized empty Git repository in /mnt/hgfs/D/SourceCode/.git/
user@ubuntu_all:/mnt/hgfs/D/SourceCode$ 
