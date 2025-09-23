# Challenge Name
implicit relative paths

## My solve
**Flag:** `pwn.college{YxC0BsMHQ8nC4DmbC6rw4RKwe39.QXxUTN0wyNzEzNzEzW}`

```bash
Connected!
hacker@paths~implicit-relative-path:~$ /challenge/run
Incorrect...
You are not currently in the /challenge directory.
Please use the `cd` utility to change directory appropriately.
hacker@paths~implicit-relative-path:~$ cd /challenge
hacker@paths~implicit-relative-path:/challenge$ run
bash: run: command not found
hacker@paths~implicit-relative-path:/challenge$ ./run
Correct!!!
./run is a relative path, invoked from the right directory!
Here is your flag:
pwn.college{YxC0BsMHQ8nC4DmbC6rw4RKwe39.QXxUTN0wyNzEzNzEzW}
```
## Incorrect tangents I went on
tried to invoke run  directly wihtout relative path

## What I learned
invoking run alone inside the /challenge directory wont work unless we implicitly call it using its relative path.
as mentioned on pwn.college-
"This will not invoke /challenge/run. This is actually a safety measure:
if Linux searched the current directory for programs every time you entered a naked path, 
you could accidentally execute programs in your current directory that happened to have the
same names as core system utilities!"

## References 
None
