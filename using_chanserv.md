How to setup an IRC Channel using Anope's NickServ and ChanServ
=====

Join an IRC Server  
```
/server server_name
```

Choose a nickname
```
/nick new_nickname
```

Register the nickname to the IRC server
```
/msg NickServ REGISTER <passowrd> <email>
```

Login to the nickname
```
/msg NickServ IDENTIFY <password>
```

Join a channel on the IRC Server
```
/join #channel_name
```

Register the Channel that was created to the Nickname that opened it
```
/msg ChanServ REGISTER <channel> <description>
```

Give the listed name Auto OP permissions to the channel
```
/msg ChanServ AOP #channel_name ADD <nickname>
```

Set a topic for the channel that everyone will see when joining the channel. This channel topic is persistent. 
```
/msg ChanServ TOPIC #channel_name SET <topic>
```

Lock the Topic to be only changable by users with the TOPIC permissions. Use UNLOCK to disable this security. 
```
/msg ChanServ TOPIC #channel_name LOCK
```
