GYT is a broken leg inspired app, made by Mindaugas Krivickas.
Logo of GYT, representing anime runner girl is dedicated for Gytautė 
Martyna made with Hotpot: https://hotpot.ai

For Windows users, in terminal execute:
1. "set-executionpolicy remotesigned -scope currentuser"
2. "pip install pyinstaller"
3. "pyinstaller --onefile --windowed --clean gui.py"
4. Go into dist directory and double click gui.exe file

For MacOS users:
1. From https://brew.sh install homebrew.
2. From website https://sveinbjorn.org/platypus execute command:
 "$ brew install --cask platypus" in terminal
3. When Platypus is installed, open it.
4.1 In App Name enter the "name of app".
4.2 Specify the path: "/usr/bin/python3"
4.3 Specify the path for gui.py file: "/Users/user/"name of app"/gui.py
4.4 Leave Interface as "Text Window" by default.
4.5 In "Bundled files..." section select + sign and add "functions.py" file.
4.6. Press "Create App" and select where would you like to put it.
5. Find that directory in Finder and open 'gui.py' file.
6. You might need to install PySimpleGUI if it does not work.

For Linux users:
1. Install PySimpleGUI.
2. Install pyinstaller.
3. Then run a command:
"pyinstaller --onefile --windowed --clean gui.py"
4. If get an error, install those packages:
"sudo apt-get install python3-dev" and "sudo apt-get install python-dev" and 
   repeat step 3.

Future plans:
1. Implement user login form.
2. Reminder function.
3. Subscription.