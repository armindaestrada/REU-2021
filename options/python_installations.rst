Python Installation
====================
.. warning:: Before installing Python make sure that you are inside the virtual machine running Ubuntu 20.04

Ubuntu 20.04 has Python 3 pre-installed. We need to make sure that the version is up to date. 
First let’s update and upgrade the system 
::
    sudo apt update
    sudo apt -y upgrade

Check the pre-installed version 
::
    python3 -V

To manage software packages for python install pip. 
::
    sudo apt install -y python3-pip

Using pip commands you are able to install python packages. Such as: 
::
    pip3 install numpy