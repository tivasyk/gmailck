# gmailck
A simple commandline Gmail checker bash script: will check gmail for new messages, show count and list subjects of 20 most recent unread emails

## Usage: 
```
./gmail [username]
```

[username] is optional, the script will ask for the Gmail login if not provided. Gmail password is not stored in any way and will be asked every 
time.

## Setup
Just copy the script to ~/bin (or elsewhere) and make sure the dependencies are installed. Optionally set the subject length as a readonly variable 
in the script.

Dependencies:
curl, sed

## Known issues
Gmail's two-step authentication not implemented
