install nodejs
------------------
curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash -
sudo apt-get install -y nodejs
	
sudo apt-get install npm
sudo ln -s /usr/bin/nodejs /usr/bin/node


create directory
------------------------
    - public            <!-- holds all our files for our frontend angular application -->
    ----- core.js       <!-- all angular code for our app -->
    ----- index.html    <!-- main view -->
    - package.json      <!-- npm configuration to install dependencies/modules -->
    - server.js         <!-- Node configuration -->


install modules
------------
hdit1505@CS1-46:~/todo$ npm install



start server:
------------------------
node server.js
