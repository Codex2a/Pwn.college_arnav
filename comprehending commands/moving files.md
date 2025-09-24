# Challenge Name
moving files

## My solve
**Flag:** `pwn.college{cqnxEiMO414F9hYEC3Up5yQCjiT.0VOxEzNxwyNzEzNzEzW}'

```bash
Connected!
hacker@commands~moving-files:~$ ls
f  w
hacker@commands~moving-files:~$ mv /flag /tmp/hack-the-planet
Correct! Performing 'mv /flag /tmp/hack-the-planet'.
hacker@commands~moving-files:~$ cd /tmp
hacker@commands~moving-files:/tmp$ ls
bin  hack-the-planet  hsperfdata_root  tmp.TpSOPGOVKK
hacker@commands~moving-files:/tmp$ cat hack-the-planet
cat: hack-the-planet: Permission denied
hacker@commands~moving-files:/tmp$ /challenge/check
Congrats! You successfully moved the flag to /tmp/hack-the-planet! Here it is:
pwn.college{cqnxEiMO414F9hYEC3Up5yQCjiT.0VOxEzNxwyNzEzNzEzW}
```
## Incorrect tangents I went on
none

## What I learned
how to move files



## References 
none
