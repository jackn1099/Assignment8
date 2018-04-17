# Assignment8
# Project 8 - Pentesting Live Targets

Time spent: 10 hours spent in total

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

Vulnerability #1: SQL Injection on saleperson URL

Vulnerability #2: __________________


## Green

Vulnerability #1: USER ENUMERATION on sign in, bold if user exists

Vulnerability #2: XSS on comment feedback section


## Red

Vulnerability #1: IDOR can find salesperson who should not be shown by changing id

Vulnerability #2: CSRF comment on green with following code

<form action="https://35.224.49.128/red/public/staff/states/show.php?id=1" method="POST">
<input type="hidden" name="name" value="4"/>
<input type="submit" value="View my pictures"/>
</form>

sign into green and click view pictures button


## Notes

Describe any challenges encountered while doing the work
