# Project 10 - Fortress Globitek

Time spent: **X** hours spent in total

> Objective: Create an intentionally vulnerable version of the Globitek application with a secret that can be stolen.

### Requirements

- [x] All source code and assets necessary for running app
- [x] `/globitek.sql` containing all required SQL, including the `secrets` table
- [x] GIF Walkthrough of compromise
- [x] Brief writeup about the vulnerabilities introduced below

### Vulnerabilities
The fields aren't santized and you are able to do sql injection.
With this vulnerability the user will be able to enumerate the users and find th admin account.
With the admin account they are able to pull out the password hash of the admin account.
Then using hashcat they can find the matching password which is the flag to this challenge.

Describe the vuln(s) here.
