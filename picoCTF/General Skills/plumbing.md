

# plumbing

<br>

## PROBLEM

<br>


> Sometimes you need to handle process data outside of a file.    
    Can you find a way to keep the output from this program and search for the flag?    
    Connect to jupiter.challenges.picoctf.org 7480

<br>



## SOLUTION

<br>

1. Use the below command to fetch the details and store in a txt file.

<br>

```

nc jupiter.challenges.picoctf.org 7480 >> a.txt

```

<br>

2. Use the grep or Open the file in code editor and search with "PICO" - It will show the flag.

<br>

## LEARNINGS

<br>

1. [Piping](https://www.geeksforgeeks.org/piping-in-unix-or-linux/)