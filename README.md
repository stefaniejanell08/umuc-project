# umuc-project
project for UMUC495

# instruction to setup the project
(1)	We will need a http server. The easiest to get is Node http server.

  a.	First we will install node package manager, npm
  
  b.	Go to https://nodejs.org/en/download/current/ and download Node JS. The NPM package manager will be automatically installed with it.
  
(2)	Install Node Http server by opening Command Prompt and entering this command: 
npm install http-server -g

(3)	Download the repo from git hub by either cloning or performing: git clone https://github.com/iEmrul/umuc-project.git

(4)	The repo will be downloaded as a folder. Open command prompt and enter:
http-server (path to file name)
Note: easiest to grab path to file by just dragging the folder directly to the command prompt and dropping it

(5)	The node server will start (Take a note of the command line to see what port the server is running. It will be something like http://127.0.0.1:8080. This is the url of the app. However the app will still not work because you need to provide your own api key.

(6)	Go to developer.mapquest.com, open a free account 

  a.	Then “create a new key”, give it any name and keep the key safe.
  
(7)	Open key.js and type: const KEY = “your key”, just fill it with your key

(8)	Now the app should run without any error

(9) Enter the location by either clicking access my location or manually entering any location
