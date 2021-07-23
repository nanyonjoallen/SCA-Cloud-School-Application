Getting started
- stable internet connection
- install homebrew
- install java8
- install jenkins -brew install jenkins-lts
- start the jenkins server -brew services start jenkins-lts
this will open the port at which the server is running at in the browser(localhost:8080) and a dashboard will appear

GITHub
- Create a repository in git hub
- open a text editor and put in a few lines of code
- Push the code to git hub.

Connecting jenkins to git
- In the jenkins dashboard, create a new job , give it a name and  select freestyle 
- give the job a description
- go to source management and select git ...enter the git repository url
- go to build environment and add a build eg python hello.py(this is the name of the file you are working on locally)
- then save

- go to dashboard and click build

