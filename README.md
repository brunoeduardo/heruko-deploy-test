# Heruko deploy test

The objective of this project is to test deployment process on Heroku platform.

The project use Angular version 7.3.8.

To deploy on Heroku server create a file "server.js" to run the project.
 
After that some items are changed in package.json:

  - Add items on dependencies, like angular/cli versions 
  
  - Add "engines" key with node and npm versions

  - On the scripts I add the "heroku-postbuild" key

  - Change the script start to call the new file created before.

  