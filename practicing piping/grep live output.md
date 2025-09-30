# Challenge Name
grepping live output


# My solve
**Flag:** `pwn.college{47yaIIN-SUKyOjiwiIWbexsweQq.QX5EDO0wyNzEzNzEzW}`

```bash
Connected!
hacker@piping~grepping-live-output:~$ /challenge/run | grep flag
[INFO] WELCOME! This challenge makes the following asks of you:
[INFO] - the challenge checks for a specific process at the other end of stdout : grep
[INFO] - the challenge will output a reward file if all the tests pass : /challenge/.data.txt

[HYPE] ONWARDS TO GREATNESS!

[INFO] This challenge will perform a bunch of checks.
[INFO] If you pass these checks, you will receive the /challenge/.data.txt file.

[TEST] You should have redirected my stdout to another process. Checking...
[TEST] Performing checks on that process!

[INFO] The process' executable is /nix/store/8b4vn1iyn6kqiisjvlmv67d1c0p3j6wj-gnugrep-3.11/bin/grep.
[INFO] This might be different than expected because of symbolic links (for example, from /usr/bin/python to /usr/bin/python3 to /usr/bin/python3.8).
[INFO] To pass the checks, the executable must be grep.

[PASS] You have passed the checks on the process on the other end of my stdout!
[PASS] Success! You have satisfied all execution requirements.
[FLAG] Here is your flag:
flagellum's
flagpole's
flagons
flagstaff's
persiflage
flags
flagellums
flagpoles
flagellation's
flagships
flagging
flagpole
flagellated
flagon's
flagstaffs
flagellate
flagellating
flagstone
flagstaff
camouflages
flagon
camouflaged
camouflage's
conflagration's
flagrantly
flagship
flagellum
flag
flagged
camouflage
flag's
camouflaging
unflagging
flagrant
flagella
conflagration
flagstones
conflagrations
flagellation
flagellates
flagstone's
flagship's
persiflage's

hacker@piping~grepping-live-output:~$ /challenge/run | grep pwn.college
[INFO] WELCOME! This challenge makes the following asks of you:
[INFO] - the challenge checks for a specific process at the other end of stdout : grep
[INFO] - the challenge will output a reward file if all the tests pass : /challenge/.data.txt

[HYPE] ONWARDS TO GREATNESS!

[INFO] This challenge will perform a bunch of checks.
[INFO] If you pass these checks, you will receive the /challenge/.data.txt file.

[TEST] You should have redirected my stdout to another process. Checking...
[TEST] Performing checks on that process!

[INFO] The process' executable is /nix/store/8b4vn1iyn6kqiisjvlmv67d1c0p3j6wj-gnugrep-3.11/bin/grep.
[INFO] This might be different than expected because of symbolic links (for example, from /usr/bin/python to /usr/bin/python3 to /usr/bin/python3.8).
[INFO] To pass the checks, the executable must be grep.

[PASS] You have passed the checks on the process on the other end of my stdout!
[PASS] Success! You have satisfied all execution requirements.
pwn.college{47yaIIN-SUKyOjiwiIWbexsweQq.QX5EDO0wyNzEzNzEzW}


## Incorrect tangents I went on
tried using flag as the word to grep with

## What I learnt
learnt to grep for value passed through /challenge/run

## References 
none
