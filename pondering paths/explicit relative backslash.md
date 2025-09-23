# Challenge Name
explicit relative paths

## My solve
**Flag:** `pwn.college{cnIVHaDwNC3jm5ypD80Son5HYVJ.QXwUTN0wyNzEzNzEzW}`

```bash
Connected!
hacker@paths~explicit-relative-paths-from-:~$ /challenge/.
bash: /challenge/.: Is a directory
hacker@paths~explicit-relative-paths-from-:~$ /challenge/run
Incorrect...
You are not currently in the / directory.
Please use the `cd` utility to change directory appropriately.
hacker@paths~explicit-relative-paths-from-:~$ ./challenge
bash: ./challenge: No such file or directory
hacker@paths~explicit-relative-paths-from-:~$ cd /
hacker@paths~explicit-relative-paths-from-:/$ ./challenge
bash: ./challenge: Is a directory
hacker@paths~explicit-relative-paths-from-:/$ ./challenge/run
Correct!!!
./challenge/run is a relative path, invoked from the right directory!
Here is your flag:
pwn.college{cnIVHaDwNC3jm5ypD80Son5HYVJ.QXwUTN0wyNzEzNzEzW}
```
## Incorrect tangents I went on
tried to access challenge without entering / directory

## What I learned
I learned about using explicit relative paths

## References 
None
