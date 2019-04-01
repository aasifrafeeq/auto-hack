# auto-hack
I am kind of new here.To start i decided to make a script that automates metasploit commands to create payload,port forward and setup listener.
Currently this script is for termux in Android.
<h4><b>How to install.</b></h4>
just enter the following commands.

```pkg install git```

```git clone https://github.com/aasifrafeeq/auto-hack```

```cd auto-hack```

```chmod +x setup payload start```

```./setup```

This will install metasploit and openssh(for port forwarding)on termux.
after install metasploit and openssh

run
```./payload```

to create payload.payload.apk will be saved in your internal storage
this will also start port forwarding.
Now open a new window and run
```./start```

to start the listener


For showing active sessions type ```sessions -i```

Don't hesitate to modify the program..
Hope you liked it.
start issue if you face any problem.
