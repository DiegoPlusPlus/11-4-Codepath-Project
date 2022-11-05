# Pen Testing Live Targets

Time spent: **11** hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:

* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each color is vulnerable to only 2 of the 6 possible exploits. First discover which color has the specific vulnerability, then write a short description of how to exploit it, and finally demonstrate it using screenshots compiled into a GIF.

## Blue

Vulnerability #1: Session Hijacking/Fixation

Description: The attacker is able to steal the session of the admin.


## Green

Vulnerability #1: User Enumeration

Description: The label will be bolded if the username exists. These is giving away information that may lead to an attacker being able to log in to anothers account.


## Red

Vulnerability #1: Insecure Direct Object Reference

Description: Changing the id # on the URL can show users revealing information.

