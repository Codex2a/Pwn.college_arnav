# Challenge Name
more catting practice

## My solve
**Flag:** `pwn.college{E-Z3YjgHA3TKh0NaRdWA3WWDwUK.QXwITO0wyNzEzNzEzW}`

```bash
Connected!
You cannot use the 'cd' command in this level, and must retrieve the flag by
absolute path. Plus, I hid the flag in a different directory! You can find it
in the file /lib/x86_64-linux-gnu/dri/flag. Go cat it out **without** cding
into that directory!
hacker@commands~more-catting-practice:~$ cat /flag
cat: /flag: No such file or directory
hacker@commands~more-catting-practice:~$ cat /lib
cat: /lib: Is a directory
hacker@commands~more-catting-practice:~$ cat /lib/x86_64-linux-gnu/dri/flag
pwn.college{E-Z3YjgHA3TKh0NaRdWA3WWDwUK.QXwITO0wyNzEzNzEzW}
```
## Incorrect tangents I went on
tried to cat /flag and then trying to cat /lib assuming it would cat the required flag

## What I learned
cat command for absolute path requires the whole absolute path


## References 
none
