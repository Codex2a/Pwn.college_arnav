# Challenge Name
linking files

## My solve
**Flag:** `pwn.college{ARgPonzwCJJjpZ3dVAMd7mh3Il0.QX5ETN1wyNzEzNzEzW}'

```bash
Connected!
hacker@commands~linking-files:~$ ln -s /flag ~/not-the-flag
hacker@commands~linking-files:~$ /challenge/flag
bash: /challenge/flag: No such file or directory
hacker@commands~linking-files:~$ /challenge/not-the-flag
bash: /challenge/not-the-flag: No such file or directory
hacker@commands~linking-files:~$ /challenge
bash: /challenge: Is a directory
hacker@commands~linking-files:~$ /challenge/catflag
About to read out the /home/hacker/not-the-flag file!
pwn.college{ARgPonzwCJJjpZ3dVAMd7mh3Il0.QX5ETN1wyNzEzNzEzW}```

## Incorrect tangents I went on
tried to invoke challenge directory and not-the-flag instead of catflag


## What I learned
how to link files

## References 
none
