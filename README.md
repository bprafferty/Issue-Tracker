Author: 
    Brian Rafferty

Manifest: 
    index.html
    main.js

Description:
    This website operates as an internal database to monitor bugs within code for a company. If a bug arises, then an engineer can fill out the webpage describing the nature of the bug, the line which the bug occurs, the severity of the bug, and which engineer on the team would be best suited to debug the code. Once a bug has been described and submitted, the engineer assigned to the task of debugging can formulate their solution, and then notify the database that the bug is eliminated by clicking on the button labeled Fix. An admin on the webpage can then do main- tenance and remove any old issues that have already been fixed by clicking the button labeled Delete.

Note:
    This website is ran on my local machine by using the live-server package contained
    within npm. To download live-server, simply open your command line and enter:
        $ npm install -g live-server
    If issues arise, such as permissions are not enabled for writing, try this instead:
        $ sudo npm install -g live-server
    Once live-server is installed, run this web application by moving directories with the command line until you are in the directory containing both index.html and main.js. Once you are in the correct directory, enter on the command line:            $ live-server
    This will start the webpage up in your browser, and you can begin tracking bugs.