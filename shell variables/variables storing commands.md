# Challenge Name
variables storing command


# My solve
**Flag:** `pwn.college{Q5szp1jvYQ4I9XeLnrGKRcahPGH.QX1cDN1wyNzEzNzEzW}`

```bash
Connected!
Connected!
hacker@variables~storing-command-output:~$ PWN=$(cat /challenge/run)
hacker@variables~storing-command-output:~$ echo $PWN
#!/opt/pwn.college/bash if [ -t 1 ] || [ ! -f /tmp/subshell ] then fold -s >&2 <<< "You are not running me via Command Substitution! Please make sure to run me with command substitution." exit 1 elif [ ! -f /tmp/dstvar ] then fold -s >&2 <<< 'You do not appear to be reading into a variable... Make sure to read me into a variable, e.g.:' echo ' VAR_NAME=$(/challenge/run)' >&2 exit 2 fi [ -f /tmp/dstvar ] && read DSTVAR < /tmp/dstvar if [ "$DSTVAR" != "PWN" ] then fold -s >&2 <<< "You are reading into the $DSTVAR variable, but you should read into the PWN variable. I am redacting the flag!" echo "pwn.college{REDACTED}" exit 3 fi fold -s >&2 <<< "Congratulations! You have read the flag into the PWN variable. Now print it out and submit it!" cat /flag
hacker@variables~storing-command-output:~$ cat /flag
cat: /flag: Permission denied
hacker@variables~storing-command-output:~$ PWN=$(/challenge/run)
Congratulations! You have read the flag into the PWN variable. Now print it out
and submit it!
hacker@variables~storing-command-output:~$ echo $PWN
pwn.college{Q5szp1jvYQ4I9XeLnrGKRcahPGH.QX1cDN1wyNzEzNzEzW}
```

## Incorrect tangents I went on
used CAT in the first statement

## What I learnt
how to store commands in variabels

## References 
none
