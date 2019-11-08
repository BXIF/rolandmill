# Establish connection
1. Open up Command Prompt, make sure that you're in the jose root directory (it should say C:\Users\jose>)
2. Type in cd mods\js\Windows\
3. This gets you into the Windows folder (C:\Users\jose\mods\js\Windows>) type in node printserverWin.js 127.0.0.1 1234, which instantiates a websocket that allows the laptop to communicate with the SRM-20. If you're successful, you'll get the following response in the Command Prompt window (listening for connection from client address 127.0.0.1 on server port 1234)

Set up program
4. Go to mods.cba.mit.edu – I like to use Chrome or Firefox
5. Right-click and select programs > open server program>Roland mill SRM-20 PCB png 

Troubleshooting
6. Take a look at the section labeled WebSocket device under status it should say socket opened
7. Change the origin coordinates in the Roland SRM-20 milling machine section (eg. x:20 – I typically like to leave a generous z of at least 25 so not to break the endmill) press the move to origin button. The machine should respond and move accordingly.
