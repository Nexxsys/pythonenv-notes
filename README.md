# pythonenv-notes

## /usr/bin/python3

## Python 3
https://pip.pypa.io/en/stable/installing/

sudo python3 ~/Downloads/get-pip.y

pip3 install virtualenv
pip3 install --upgrade pip

sudo apt-get install python-pip
sudo apt-get install npm

### create the virtual environment
http://docs.python-guide.org/en/latest/dev/virtualenvs/

virtualenv -p /usr/bin/python3 pytempapi

### In the case of a File Not Found for pipenv or virtualenv
sudo -H pip3 install -U pipenv

### BASH script
echo " Please provide directory name and press [ENTER]"
read newproject
virtualenv -p /usr/bin/python3 $newproject

### Activate the application
ex. source pytempapi/bin/activate

### other installs
pip3 install requests

### When you are done with the environment (virt)
deactivate
