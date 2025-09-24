# Challenge Name
listing files

## My solve
**Flag:** `not found yet'

```bash

hacker@commands~listing-files:~$ ls /challenge
11739-renamed-run-7891  DESCRIPTION.md
hacker@commands~listing-files:~$ cat 11739-renamed-run-7891
cat: 11739-renamed-run-7891: No such file or directory
hacker@commands~listing-files:~$ cd challenge
bash: cd: challenge: No such file or directory
hacker@commands~listing-files:~$ cd /challenge
hacker@commands~listing-files:/challenge$ cat 11739-renamed-run-7891
#!/opt/pwn.college/bash

echo "Yahaha, you found me! Here is your flag:"
cat /flag
hacker@commands~listing-files:/challenge$ /challenge/11739-renamed-run-7891
Yahaha, you found me! Here is your flag:
pwn.college{Mm_bLrWHmg2RpDS35FQ9zSucKPp.QX4IDO0wyNzEzNzEzW}
hacker@commands~listing-files:/challenge$```

## Incorrect tangents I went on
used cat to access flag rather than /challenge/flag

## What I learned
how to list files

## References 
none
