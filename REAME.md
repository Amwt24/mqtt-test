# Monitoring system

## Requirements


* [Requirements file](requirements.txt)
* Python 3.10.13v (Anaconda)
* Mysql DB

## To start
1. Install dependecies


``` bash
$ cd MQTT-TEST
$ pip install -r compiled_requirements.txt
```

2. Create a database and a table (Mysql)
3. [Change the .env file](src/connections/db/.env)
3. To launch the project, run the following commands:


``` bash
$ cd MQTT-TEST/src
$ python init.py
```