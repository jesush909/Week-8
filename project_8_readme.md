# Project 8 - Pentesting Live Targets

Time spent: 6 hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:
* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each version of the site has been given two of the six vulnerabilities. (In other words, all six of the exploits should be assignable to one of the sites.)

## Blue

Vulnerability #1: In the blue site when choosing a specific salesperson you can add the sql injection in the end of the url and it won't redirect you like the red and green site does.
![ALT text](https://imgur.com/a/C5aUf)

Vulnerability #2: In the blue site when logged in as admin you can get your phpsessionid and on a different browser while not logged in the blue site you can view your phpsessionid and replace it with the admin phpsessionid. Onced changed you can it will log you in automatically as an admin.
![ALT text](https://imgur.com/a/pZsIk)

## Green

Vulnerability #1 In the log in section for green I tried logging with nonexisting usernames the text was plain but when I tried with a real username the text became bold letting me know it is an existing account.
![ALT text](https://imgur.com/a/zXTyj)

Vulnerability #2: In the contact us section for the green site I inputed the script and as the admin logs in and checks the feedback it will be executed
![ALT text](https://imgur.com/a/C5aUf)

## Red

Vulnerability #1: In the red site while looking at a specific salesperson you can see the number attached to the salesperson and it allows you to modify the number to switch to different salesman without any permissions.
![ALT text](https://imgur.com/a/oHb2l)

Vulnerability #2: 



## Notes

I first researched some common website vulnerabilities and it was basically like some of the labs we have done so it helped me out to be able to know how find the vulnerabilities.

