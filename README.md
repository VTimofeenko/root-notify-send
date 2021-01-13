# About

Set of two scripts to be run as root and display notifications to logged in users.

First script (`root-notify-send`) sends the message to all currently logged in users by iterating over processes of window managers. Accepts parameters which are passed to the notify-send.

Second script (`root-notify-user`) sends the message to a single user. The username is passed as the first parameter, the rest of them is passed to notify-send.

# Example usage

```
# root-notify-send "A"
```

# Installation
