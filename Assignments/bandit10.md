# Bandit Level 10 to 11 Writeup


Author: [Kunwar Preet Singh](https://github.com/enkryp)

Problem Page: [bandit10](https://overthewire.org/bandit/bandit11.html) 

## List of Commands Used
```
base64
```

## Walkthrough

The lvl was simply about decoding the base64 data. Which is easily acheived by "base64 -d".

## Password
IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR

## Bash/Python script to automate the process
```
sshpass -p truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk ssh bandit10@bandit.labs.overthewire.org -p 2220 base64 -d data.txt


```

