# Challenge Name
help for builtin

## My solve
**Flag:** `pwn.college{wPFuZSKx7O_juUHAj6zeQqDFyqn.QX0ETO0wyNzEzNzEzW}'

```bash
Connected!
hacker@man~help-for-builtins:~$ help challenge
challenge: challenge [--fortune] [--version] [--secret SECRET]
    This builtin command will read you the flag, given the right arguments!

    Options:
      --fortune         display a fortune
      --version         display the version
      --secret VALUE    prints the flag, if VALUE is correct

    You must be sure to provide the right value to --secret. That value
    is "wPFuZSKx".
hacker@man~help-for-builtins:~$ challenge --secret wPFuZSKx
Correct! Here is your flag!
pwn.college{wPFuZSKx7O_juUHAj6zeQqDFyqn.QX0ETO0wyNzEzNzEzW}

## Incorrect tangents I went on
none

## What I learned
how to use builtins and how to ask for help in builtins

## References 
none
