# Challenge Name
changing directory

## My solve
**Flag:** `pwn.college{QaMH16b1NaGWwOghVurlM8FRtCR.QX2QTN0wyNzEzNzEzW}`

```bash
Connected!
hacker@paths~position-thy-self:~$ /challenge/run
Incorrect...
You are not currently in the /usr/include directory.
Please use the `cd` utility to change directory appropriately.
hacker@paths~position-thy-self:~$ cd
hacker@paths~position-thy-self:~$ /challenge/run
Incorrect...
You are not currently in the /usr/include directory.
Please use the `cd` utility to change directory appropriately.
hacker@paths~position-thy-self:~$ cd/usr/include
bash: cd/usr/include: No such file or directory
hacker@paths~position-thy-self:~$ /usr/include
bash: /usr/include: Is a directory
hacker@paths~position-thy-self:~$ cd /usr/include
hacker@paths~position-thy-self:/usr/include$ /challenge/run
Correct!!!
/challenge/run is an absolute path, invoked from the right directory!
Here is your flag:
pwn.college{QaMH16b1NaGWwOghVurlM8FRtCR.QX2QTN0wyNzEzNzEzW}
```
## Incorrect tangents I went on
not leaving space between cd and /usr/include which made it a different directory
tried to run challenge directly without going to the usr/include directory

## What I learned
how to change and choose respective directory 

## References 
None
