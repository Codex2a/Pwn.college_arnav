# Challenge Name
touching files

## My solve
**Flag:** `pwn.college{0CYoplzylzz8X9RRzuVs7RLoOQJ.QXwMDO0wyNzEzNzEzW}`

```bash
Connected!
hacker@commands~touching-files:~$ cd/ tmp
bash: cd/: No such file or directory
hacker@commands~touching-files:~$ cd /tmp
hacker@commands~touching-files:/tmp$ touch pwn
hacker@commands~touching-files:/tmp$ touch college
hacker@commands~touching-files:/tmp$ ls
bin  college  hsperfdata_root  pwn  tmp.TpSOPGOVKK
hacker@commands~touching-files:/tmp$ /challenge/run
Success! Here is your flag:
pwn.college{0CYoplzylzz8X9RRzuVs7RLoOQJ.QXwMDO0wyNzEzNzEzW}

```
## Incorrect tangents I went on
none

## What I learned
how to create files

## References 
none
