# Challenge Name
helpful programs

## My solve
**Flag:** `pwn.college{Is_jmXKC3k5L4fj25wX6nmemUxO.QX3IDO0wyNzEzNzEzW}'
```bash
Connected!
hacker@man~helpful-programs:~$ --help
bash: --help: command not found
hacker@man~helpful-programs:~$ /challenge/challenge --help
usage: a challenge to make you ask for help [-h] [--fortune] [-v] [-g GIVE_THE_FLAG] [-p]

optional arguments:
  -h, --help            show this help message and exit
  --fortune             read your fortune
  -v, --version         get the version number
  -g GIVE_THE_FLAG, --give-the-flag GIVE_THE_FLAG
                        get the flag, if given the correct value
  -p, --print-value     print the value that will cause the -g option to give you the flag
hacker@man~helpful-programs:~$ /challenge/challenge -g
usage: a challenge to make you ask for help [-h] [--fortune] [-v] [-g GIVE_THE_FLAG] [-p]
a challenge to make you ask for help: error: argument -g/--give-the-flag: expected one argument
hacker@man~helpful-programs:~$ /challenge/challenge -g GIVE_THE_FLAG
usage: a challenge to make you ask for help [-h] [--fortune] [-v] [-g GIVE_THE_FLAG] [-p]
a challenge to make you ask for help: error: argument -g/--give-the-flag: invalid int value: 'GIVE_THE_FLAG'
hacker@man~helpful-programs:~$ /challenge/challenge -p
The secret value is: 354
hacker@man~helpful-programs:~$ /challenge/challenge -g 354
Correct usage! Your flag: pwn.college{Is_jmXKC3k5L4fj25wX6nmemUxO.QX3IDO0wyNzEzNzEzW}
hacker@man~helpful-programs:~$```

## Incorrect tangents I went on
didnt read fully and assumed that -g GIVE_THE_FLAG is the full documentation rather than a number

## What I learned
how to ask for help

## References 
none
