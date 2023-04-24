

# Big Zip

<br>

## PROBLEM

<br>


> Unzip this archive and find the flag.

<br>



## SOLUTION

<br>

1. Download the zip file & unzip it using below command

<br>

```
unzip big-zip-files.zip

```

<br>

2. Using the below mentioned grep command you can find the flag

<br>

```
grep -iR 'PICO' ./big-zip-files

```

<br>

## LEARNINGS

<br>

1. [Grep](https://www.geeksforgeeks.org/grep-command-in-unixlinux/)