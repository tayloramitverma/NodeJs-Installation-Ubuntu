# ubuntu-nodejs-installation

How we can setup angular in ubuntu os. Below steps are written for solved angular installation erros and version support for clean and clear developement environment.

1) Clear previous node version and all cache related to node.

a).  sudo rm -rf /usr/local/bin/node-gyp 
b).  sudo rm -rf /usr/local/bin/npm
c).  sudo rm -rf /usr/local/bin/npx
d).  sudo rm -rf /usr/local/lib/node_modules/

2) Now cleaning node files in home directory, for precaution:

a).  rm -rf ~/.node-gyp/
b).  rm -rf ~/.npm/

3) Then finally uninstall node.

a).  sudo apt-get remove --purge nodejs

Then install node again 

a).  sudo apt-get install nodejs

then run: sudo npm install -g npm

That's it. 

Now you can check node version using terminal command: 

node -v

and npm version using: 

npm -v

Thank you, Have a great start.
