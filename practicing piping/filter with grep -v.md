# Challenge Name
filter with grep -v


# My solve
**Flag:** `pwn.college{U6kkoxF9ndBG7wivlIshv7os6DF.0FOxEzNxwyNzEzNzEzW}`

```bash
Connected!
hacker@piping~filtering-with-grep-v:~$ cat /challenge/run | grep -v DECOY
#!/opt/pwn.college/bash

FLAG=$(cat /flag)
FLAG_CONTENT=$(sed 's/pwn\.college{\(.*\)}/\1/' <<< "$FLAG")

# Generate 1000+ lines with decoys and the real flag
REAL_FLAG_LINE=$((RANDOM % 1000 + 1))

for i in {1..1200}; do
    if [ $i -eq $REAL_FLAG_LINE ]; then
        # Print the real flag
        echo "$FLAG"
    else
        echo -n "pwn.college{"
        echo "}"
    fi
done
hacker@piping~filtering-with-grep-v:~$ /challenge/run | grep -v DECOY
pwn.college{U6kkoxF9ndBG7wivlIshv7os6DF.0FOxEzNxwyNzEzNzEzW}


## Incorrect tangents I went on
tried to cat the grepped function

## What I learnt
realised  grep prints the grepped output by itself. learnt how to use -v to print all lines without DECOY

## References 
none
