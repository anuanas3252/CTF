
# strings it


## PROBLEM

> Can you find the flag in file without running it?



## SOLUTION

Yep... This one was very interesting & Little bit confused...

1. Download the File

2. CHeck the file type - Exe file

3. Make it executable

```
chmod +x strings
```

3. Go for help argument the downloaded file (Note that : don't forget to give ./ otherwise it will show help section of strings command)

```
./strings -h
```
4. It showed to check for strings function .. COnfusion arise Here , This strings function mention is not our downloaded file - its strings command

5. I gone for help section of the strings command

```
strings -h
```

6. I don't know which arguments to select from the given ones. So what I did was I chose to go with -a (all argument) and store the result to a text file

```
strings -a strings >> a.txt
```

7. Now I opened the file in code editor & searched for "pico" and it showed me the Flag

## LEARNINGS

1. [string Functions ](https://linux.die.net/man/1/strings)
