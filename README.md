# pytest-automation

## Install python
sudo apt install python3.8

## Install pip
sudo apt-get update
sudo apt-get -y install python3-pip

## Freeze all pip3 installations
pip freeze > requirements.txt

## Creating the virtual environment
sudo apt install -y python3-virtualenv
virtualenv venv
pip uninstall virtualenv

## Activating virtualenv on Linux Ubuntu /macOS
source venv/bin/activate

## Activate virtualenv on Windows 10
.\venv\Scripts\activate

## Installing Python dependencies
pip install -r requirements.txt