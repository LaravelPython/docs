# Installation

## Installation
Larapy has following system requirements.
* python > 3.6
* pip3

### Installing Larapy
Install python and pip first
```
sudo apt install python3.7 python3-pip
```
Larapy installation is so simple. You need to have python >3.x and pip3 installed in your machine.
Larapy strongly suggest to use pipenv to manage virtual environment.
```
pip3 install larapy-installer pipenv
```
### Creating Larapy Projects
Once Larapy installed, larapy command will available to your terminal. For instance, ```larapy new blog``` will create a directory named blog containing fresh larapy application.

```
larapy new blog
```

Install dependency
```
pipenv install
```
Activate virtual env
```
pipenv shell
```
Server project
```
python3 serve
```