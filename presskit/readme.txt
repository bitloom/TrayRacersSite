Tray Racers Presskit Guide by James   !
-----------------------------------\\[-j-]

To make changes to the presskit you will need:

- a clone of the TrayRacersSite github repo
- a copy of python installed https://www.python.org/downloads/
- a copy of nodejs installed https://nodejs.org/en/

Build instructions:

- open the command prompt (windows key then type cmd and hit enter)
- install presskit by entering "npm install -g presskit" (only need to do this once)
- navigate to the presskit folder by entering "cd", pressing space and dragging in the /presskit/data folder of the repo
- then enter "presskit build", after a short time it should say "done!"
- open the presskit/data/build folder and launch index.html to test

Making it live:

- when you are ready to make your changes live:
- delete the old build files in the /presskit root folder i.e. the /css, /images, /js, /product folders and index.html
- !! make sure not to delete the /data folder, readme.txt or /.vs folder!
- now drag the contents of the /presskit/data/build folder to the /presskit root folder
- launch /presskit/index.html to test it again
- finally push the git repo ignoring any unnecessary files
- go to trayracers.com to see the changes


More info here:

https://github.com/pixelnest/presskit.html