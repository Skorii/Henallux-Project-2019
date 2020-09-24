# Python Henallux Project 2019
Usage informations about master.py and slave.py classes

## Installation
```cmd
pip install master-slave
```

## Class Master

Usage:
```python
from master_slave.master import *

master = Master(address="", port=50000)
   # address = address to listen to (empty mean listenning on all addresses)
   # port = listening port 
master.start()
```

## Class Slave

Usage:
```python
from master_slave.slave import *

slave = Slave(address="192.168.0.10", port=50000)  
   # address = address of master
   # port = listening port of master
slave.start()
```
