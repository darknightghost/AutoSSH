# AutoSSH

##How to use it?

###1.Fill a command list. 

The command list is a python3 script file, here is a sample:

```
host = target-host
usrname = target-user-name
passwd = target-password
port = target-port
encoding = target-host-shell-encoding

prompt = target-shell-prompr-after-logging-in

#((command1, prompt1),
#   (command2, prompt2),
#   (command3, prompt3),
#   ...
#   (command4, prompt4))
commands = (("command1", "prompt1"),
				("command2", "prompt2"),
                ("command3", "prompt3"),
                ...,
                ("commandn", "promptn"))

```

###2.Run command.

Usage:
```
autossh command-list-file-path
```