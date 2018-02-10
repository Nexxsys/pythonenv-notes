# pythonenv-notes

## /usr/bin/python3
## Python 3
#sudo apt-get install python-pip
#sudo apt-get install npm
pip install virtualenv
pip install --upgrade pip

## create the virtual environment
## http://docs.python-guide.org/en/latest/dev/virtualenvs/
### ex virtualenv -p /usr/bin/python3 pytempapi

echo " Please provide directory name and press [ENTER]"
read newproject
virtualenv -p /usr/bin/python3 $newproject

## Activate the application
## source pytempapi/bin/activate

## other installs
pip3 install requests

## Install Flask # sudo
pip3 install Flask

## To execute
## python pytempapi # executes the app for local viewing only

## When you are done with the environment (virt)
## deactivate
