# Pyremote
A simple local web remote for keyboard shortcuts powered by Python

# Why This Exists

I work in a small studio as a sound engineer, and sometimes I have to record my own voice. Since there’s no one to help me with recording and editing, I decided to code this little project to free myself from the hassle. Yes, there are already some alternatives for this app, but most of them require installation, and the system we use there is using Deepfreeze. So this was more convenient for me. I figured using Python to create a simple interface to execute simple combo keys, or shortcuts, would be a good idea.


# How It Works
The functionality of this app is pretty straightforward:

•	Run the server on your PC.

•	Connect both the server and your desired client to the same network. 

•	Go to the given IP address given by the server GUI. 

•	Execute commands from the Web UI on the client. 


As a reminder, there are alternatives to this app. The only difference between this and others is portability. 

# Dependencies:
There are dependencies for this app to run (if you're running the Python code yourself):

Flask (`pip install flask`)

keyboard (`pip install keyboard`)


# Current situation
As of now, there are only pre-defined shortcuts available on the server, which were those I needed to get around the stuff I needed for myself: 
-  Cut (Ctrl+K)
-  Save (Ctrl+S)
-  Undo (Ctrl+Z)
-  Record (Shift+Space)
-  Delete (Delete)
-  Play/Pause (Space)

You may add your own shortcuts by adding the following code to the configuration: 

`<button onmousedown="startPress('X+Y')">Label</button>`

"X+Y" is your desired shortcut.


---
But who knows, maybe even other users contribute to this app.
