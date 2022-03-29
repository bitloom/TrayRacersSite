Tray Racers Presskit Guide by James   !
-----------------------------------\\[-j-]

To make changes to the presskit you will need:

- a clone of the TrayRacersSite github repo
- a copy of python installed https://www.python.org/downloads/
- a copy of nodejs installed https://nodejs.org/en/

Build instructions:

- open the command prompt (windows key then type cmd and hit enter)
- install presskit by entering "npm install -g presskit"
- navigate to the presskit folder by entering "cd", pressing space and dragging in the /presskit/data folder of the repo
- then enter "presskit build" it should say done!
- open the presskit/data/build/ folder and launch index.html

Making it live:

- when you are ready to make your changes live, drag the contents of the build folder to the presskit/ root folder
- you may need to delete some of the old build files from the /presskit root folder like images to stop them showing up
- make sure not to delete the data folder!
- now delete the build folder and push the git repo
- go to trayracers.com to see the changes, can take an hour to appear


More info here:

https://github.com/pixelnest/presskit.html