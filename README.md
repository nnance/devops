devops
======

DevOps scripts and notes

AWS Installation
===
* Create ubuntu server
* Add server to ~/.sh/config file
* ssh to server
* sudo apt-get update
* sudo apt-get install git

* git clone https://github.com/nnance/devops.git
* sh devops/ubuntu-aws/install-mongodb.sh
* sh devops/ubuntu-aws/install-nodejs.sh
* sh devops/ubuntu-aws/install-nodejs-build-tools.sh

NODE App Installation
===
* cd apps
* git clone {app}
* cd {appdir}
* sudo npm install
* bower install - if used
* grunt build - if used
* forever start {script}
