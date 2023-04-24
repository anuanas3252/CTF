

# chrono

<br>

## PROBLEM

<br>


> How to automate tasks to run at intervals on linux servers?   
    Additional details will be available after launching your challenge instance.


<br>



## SOLUTION

<br>

1. Launch the instance

2. I don't know whether I have find the Flag the right way or not

3. I checked the folder and files present in it

4. I went to root folder

5. saw a folder named "challenge" - THe name was quite interesting

6. I went it to & saw a JSON file, The flag was present in that JSON file.

<br>

### The other way

<br>

1. Looking at the challenge hint, I figured out that it is hinting towards cron tasks, stored in the /etc/crontabs file. I used cat /etc/crontab/ to find the flag now.

<br>


## LEARNINGS

<br>

1. [cron, cronjob](https://www.howtogeek.com/devops/what-is-a-cron-job-and-how-do-you-use-them/)

2. [crontab](https://www.geeksforgeeks.org/crontab-in-linux-with-examples/)