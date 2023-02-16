# INET 4031 - Lab 4 - Part 2
## Linux User Management Part 2

A list of user accounts is read into the "create-users.py" script, which then generates corresponding system accounts on the system.

## Input Format
The input to the script is a list of user accounts in the following format:
`<username>:<password>:<lastname>:<firstname>:<group1,group2,group3,...>`

The fields in the input file are separated by colons, and each line represents a single user account (:). The group field contains a list of group names, separated by commas, to which the user should belong. The script disregards lines that begin with a # since they are regarded as comments.

## Usage
The script can be executed as follows:
`sudo python3 create-users.py < create-users.input`

where create-users.input is the file containing the list of user accounts.

## Output
The script displays the status messages for each user account created, indicating when the user was added to the desired groups, given a password, and their account was established.