# Challenge Name
listing files

## My solve
**Flag:** `not found yet'

```bash
Connected!
hacker@commands~listing-files:~$ ls
f  w
hacker@commands~listing-files:~$ cat f
pwn.college{oD97X7Wl3REGYlSS7xXiDHwIFaK.QXzMDO0wyNzEzNzEzW}

hacker@commands~listing-files:~$ ls /challenge
1382-renamed-run-6860  DESCRIPTION.md
hacker@commands~listing-files:~$ cd /challenge
hacker@commands~listing-files:/challenge$ ls
1382-renamed-run-6860  DESCRIPTION.md
hacker@commands~listing-files:/challenge$ cat 1382-renamed-run-6860
#!/opt/pwn.college/bash

echo "Yahaha, you found me! Here is your flag:"
cat /flag
hacker@commands~listing-files:/challenge$ cat /flag
cat: /flag: Permission denied
hacker@commands~listing-files:/challenge$ cd ~
hacker@commands~listing-files:~$ cat /flag
cat: /flag: Permission denied

```
## Incorrect tangents I went on
not understanding how to solve
flag permission denied??

## What I learned
nothing yet

## References 
none
