# Challenge Name
making directory

## My solve
**Flag:** `pwn.college{k0go6YL45jLuN9iBsHQ-gEPRznQ.QXxMDO0wyNzEzNzEzW}'

```bash
Connected!
hacker@commands~making-directories:~$ cd tmp
bash: cd: tmp: No such file or directory
hacker@commands~making-directories:~$ cd /tmp
hacker@commands~making-directories:/tmp$ cd /pwn
bash: cd: /pwn: No such file or directory
hacker@commands~making-directories:/tmp$ mkdir /pwn
mkdir: cannot create directory ‘/pwn’: Permission denied
hacker@commands~making-directories:/tmp$ mkdir pwn
hacker@commands~making-directories:/tmp$ cd /pwn
bash: cd: /pwn: No such file or directory
hacker@commands~making-directories:/tmp$ cd pwn
hacker@commands~making-directories:/tmp/pwn$ touch college
hacker@commands~making-directories:/tmp/pwn$ /challenge/run
Success! Here is your flag:
pwn.college{k0go6YL45jLuN9iBsHQ-gEPRznQ.QXxMDO0wyNzEzNzEzW}```

## Incorrect tangents I went on
using /pwn instead of pwn alone and vice versa


## What I learned
how to make a directory

## References 
none
