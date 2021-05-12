# Bandit Level 8 to 9 Writeup


Author: [Kunwar Preet Singh](https://github.com/enkryp)

Problem Page: [bandit8](https://overthewire.org/bandit/bandit8) 

## List of Commands Used
```
sort 
uniq
```

## Walkthrough

The level was about finding the unique element in the data.txt. Uniq command was the perfect tool for the job. The sort comand can be used to sort the strings so the same elements come together the output piped to uniq (with '-u' to display the unique string) would give the pass to next lvl. 

## Password
UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR

## Bash/Python script to automate the process
```
sshpass -p cvX2JJa4CFALtqS87jk27qwqGhBM9plV ssh bandit8@bandit.labs.overthewire.org -p2220 sort data.txt | uniq -u

```

