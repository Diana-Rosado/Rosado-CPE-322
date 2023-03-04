## Lab 5

I pledge my honor that I have abided by the Stevens Honor System - Diana Rosado

### Changed directory to iot repo, update repo with git pull, change directory to lesson 5

<img src="https://github.com/Diana-Rosado/Rosado-CPE-322/blob/main/Labs/Lab6/update.png" width="800" height="600">

### Install Paho and run code to subscribe on one terminal and publish on another

```
$ sudo pip3 install -U paho-mqtt
$ git clone https://github.com/eclipse/paho.mqtt.python.git
$ cd ~/iot/lesson5
$ python3 client.py
```

### 2. Run subcpu.py on one terminal and pubcpu.py on another

Terminal 1
```
$ python3 subcpu.py
```

Terminal 3
```
$ python3 pubcpu.py
```

<img src="https://github.com/Diana-Rosado/Rosado-CPE-322/blob/main/Labs/Lab5/twoterminals.png" width="800" height="600">


