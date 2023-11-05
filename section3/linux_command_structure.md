# Structure of commands 
you type in a shell,the command’s name, its options and arguments, if required.

```bash
ping -c 1 8.8.8.8
```

the ping command, which is available on Windows and Mac as well, is used to test the network connectivity to a destination host.

* to check network connection we can ping to 8.8.8.8 which is publi DNS server from google 

* If you have any issue with your Internet connection to continue with this example, you can ping your loopback interface ip address, which is 127.0.0.1. This is the IP address of your loopbeck interface.


```bash
ping -c 1 127.0.0.1
```

* name of command is ping

* c is one of options 

* 1 is options value 

* 127.0.0.1 is command argument


all options are precede by a hyphen '-'

Its common to separate the command name,its options and arguments with one space but there is nothing wrong if you add one or more whitespaces.

In Linux, there are commands that require some options or arguments and return an error if they are run without arguments; and they are other commands that do not necessarily require options or arguments.

