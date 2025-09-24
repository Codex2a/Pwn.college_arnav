# Challenge Name
hidden files

## My solve
**Flag:** `pwn.college{4zke7jBhfHnTO6hKSmMZMbkK2Nu.QXwUDO0wyNzEzNzEzW}'

```bash
Connected!
hacker@commands~hidden-files:~$ cd /
hacker@commands~hidden-files:/$ ls
bin   challenge  etc   lib    lib64   media  nix  proc  run   srv  tmp  var
boot  dev        home  lib32  libx32  mnt    opt  root  sbin  sys  usr
hacker@commands~hidden-files:/$ ls -a
.   .dockerenv             bin   challenge  etc   lib    lib64   media  nix  proc  run   srv  tmp  var
..  .flag-177051093322176  boot  dev        home  lib32  libx32  mnt    opt  root  sbin  sys  usr
hacker@commands~hidden-files:/$ cat .flag-177051093322176
pwn.college{4zke7jBhfHnTO6hKSmMZMbkK2Nu.QXwUDO0wyNzEzNzEzW}
```
## Incorrect tangents I went on
none

## What I learned
how to list and find "hidden" files (dotted ones)


## References 
none
