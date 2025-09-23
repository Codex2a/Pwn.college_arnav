# Challenge Name
home sweet home 

## My solve
**Flag:** `pwn.college{oD97X7Wl3REGYlSS7xXiDHwIFaK.QXzMDO0wyNzEzNzEzW}`

```bash
Connected!
hacker@paths~home-sweet-home:~$ cd ~
hacker@paths~home-sweet-home:~$ /challenge/run ~/flg
The argument you provided must not have been longer than 3 characters (it's
currently 5 characters long)!
hacker@paths~home-sweet-home:~$ /challenge/run ~/f
Writing the file to /home/hacker/f!
... and reading it back to you:
pwn.college{oD97X7Wl3REGYlSS7xXiDHwIFaK.QXzMDO0wyNzEzNzEzW}
```
## Incorrect tangents I went on
assumed that argument name can be 3 char long and not entire argument.
was confused about how one must call arguement from inside home directory.

## What I learned
how to access a path from inside home directory after declaring it


## References 
www.scribd.com
