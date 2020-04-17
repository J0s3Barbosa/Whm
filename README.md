# DeviceManager
Device manager for Windows

### Whm
windows hardware manager

### About the project: 

```sh
- Project in python to manager some hardware interactions
- the purpose is automate some actions, accordantly to systems erros and monitoring it, for example, if some hardware fails, the system will monitore it and take some actions, like unistalling and installing , desabe and enable. all the options that a human would do, all the options available to make it work again.

- After installing dependecies, run the UnitTest to check if the system is getting necessary data from env file or your environment server.

-Requirements
- PyQt5
- devcon.exe - to run the code that enable and disable hardware

```

### Install dependencies:  

```sh
- install virtualenv if u dont have yet
py -m pip install virtualenv

- run the code below
py -m virtualenv venv

- activate env
. venv\scripts\activate

- install requirements
pip install -r requirements.txt

- run the code


```
### Features:  

```sh

- get all device information
- find devices by name
- enable devices
- disable devices


```
