# Challenge Name
mixing globbing

## My solve
**Flag:** `pwn.college{Y659VmFefLdsg3WVJGY2B5jwT16.QX1IDO0wyNzEzNzEzW}`

```
bash
Connected!
hacker@globbing~mixing-globs:/challenge/files$ /challenge/run file_[c*]
Error: your argument is too long! It must be 6 characters or less.
hacker@globbing~mixing-globs:/challenge/files$ /challenge/run f_[c*]
Your expansion did not expand to the requested files (challenging, educational,
pwning). Instead, it expanded to:
f_[c*]
hacker@globbing~mixing-globs:/challenge/files$ /challenge/run [cep]*
You got it! Here is your flag!
pwn.college{Y659VmFefLdsg3WVJGY2B5jwT16.QX1IDO0wyNzEzNzEzW}
```


## Incorrect tangents I went on
took few tries to get to the correct argument

## What I learnt
how to mix globbing


## References 
none
