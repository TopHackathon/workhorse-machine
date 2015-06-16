Copyright Lund&Bendsen A/S

# workhorse-machine
This machine has various tools for playing with virtualization installed. Its an Ubuntu machine.

If the script can detect your username, a user with that name will be added to the machine, 
otherwise a user "anonymous" will be added to the machine.
The default password is "developer" 

##Prerequisites 

You need git (to clone this project), vagrant (to build the machine) and Virtualbox (to run the machine) installed.
- git
- Virtualbox 4.3.10 or later
  - you should install guest additions (Virtual _may_ help you doing this)
  - you should install extension pack
- Ubuntu 14.04 or later
- vagrant 1.7.2 (http://www.vagrantup.com/downloads.html)

### Installing on Ubuntu

On ubuntu installing this would be something like

* sudo apt-get install vagrant
* sudo apt-get install virtualbox
* sudo apt-get install git
* git clone https://github.com/jwermuth/basecamp-vagrant.git
* vagrant up --provision

### Installing on windows

I have focused on Ubuntu. If you try this on Windows, feel free to make a **Pull Request** if you try this.
I friend did without hazzle on windows. Another experienced problems with curl 

"unable to get local issuer certificate"

### Installing on Mac

A friend did this without hazzle, so its possible. I have not tried it.

