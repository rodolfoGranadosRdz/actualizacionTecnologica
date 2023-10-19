# COMANDOS LINUX

```sh
ubuntu@ubuntu2004  ~/Desktop  man mkdir
MKDIR(1)                                                                           User Commands                                                                          MKDIR(1)

NAME
       mkdir - make directories

SYNOPSIS
       mkdir [OPTION]... DIRECTORY...

DESCRIPTION
       Create the DIRECTORY(ies), if they do not already exist.

       Mandatory arguments to long options are mandatory for short options too.

       -m, --mode=MODE
              set file mode (as in chmod), not a=rwx - umask

       -p, --parents
              no error if existing, make parent directories as needed

       -v, --verbose
              print a message for each created directory

       -Z     set SELinux security context of each created directory to the default type

       --context[=CTX]
              like -Z, or if CTX is specified then set the SELinux or SMACK security context to CTX

       --help display this help and exit

       --version
              output version information and exit

AUTHOR
       Written by David MacKenzie.

REPORTING BUGS
       GNU coreutils online help: <https://www.gnu.org/software/coreutils/>
       Report mkdir translation bugs to <https://translationproject.org/team/>

COPYRIGHT
       Copyright © 2018 Free Software Foundation, Inc.  License GPLv3+: GNU GPL version 3 or later <https://gnu.org/licenses/gpl.html>.
       This is free software: you are free to change and redistribute it.  There is NO WARRANTY, to the extent permitted by law.
```
```sh
ubuntu@ubuntu2004  ~/Desktop  whoami
ubuntu
```
```sh
ubuntu@ubuntu2004  ~/Desktop  history
    1  nano .zshrc
    2  exit
    3  git clone https://github.com/powerline/fonts.git\n
    4  cd fonts
    5  ll
    6  ./install.sh
    7  exit
    8  cd fonts
    9  echo "x" > x.txt
   10  git add .
   11  ll
```
```sh
ubuntu@ubuntu2004  ~/Desktop  ls
prueba_sha256.txt
```
```sh
ubuntu@ubuntu2004  ~/Desktop  pwd
/home/ubuntu/Desktop
```
```sh
ubuntu@ubuntu2004  ~/Desktop  cd ..
```
```sh
ubuntu@ubuntu2004  ~  pwd
/home/ubuntu
```
```sh
ubuntu@ubuntu2004  ~  cd Desktop
```
```sh
ubuntu@ubuntu2004  ~/Desktop  cat prueba_sha256.txt 
Hola Rodolfo Granados
```
```sh
ubuntu@ubuntu2004  ~/Desktop  mkdir prueba_dir
```
```sh
ubuntu@ubuntu2004  ~/Desktop  ls
prueba_dir  prueba_sha256.txt
```
```sh
ubuntu@ubuntu2004  ~/Desktop  rmdir prueba_dir
```
```sh
ubuntu@ubuntu2004  ~/Desktop  ls
prueba_sha256.txt
```
```sh
ubuntu@ubuntu2004  ~/Desktop  ll
total 12
drwxr-xr-x  2 ubuntu ubuntu 4096 oct  8 22:18 .
drwxr-xr-x 31 ubuntu ubuntu 4096 oct  8 22:19 ..
-rw-rw-r--  1 ubuntu ubuntu   22 oct  8 22:01 prueba_sha256.txt
```

