# Starting x11vnc in docker container 

> x11vnc is a remote connection software program that allows you access to the host's machine remotly. 
I tried starting the server as the `CMD` says `x11vnc not found`

[x11vnc commands](https://command-not-found.com/x11vnc)

> Fixed this issue by viewing the file structure from within the container when running. Found the path was not correct and there was a spelling mistake!

Also ports need to be mapped

`-p 5900:5900`
