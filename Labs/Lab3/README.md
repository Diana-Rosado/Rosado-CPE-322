## Lab 3

I pledge my honor that I have abided by the Stevens Honor System - Diana Rosado


Below are commands that are ran in the vs code terminal.

```
$ cd ~/iot  //goes to the iot folder
$ cd *3     //goes to lesson 3
$ python3 julian.py
$ python3 date_example.py
$ python3 datetime_example.py
$ python3 time_example.py
```
<img src="https://github.com/Diana-Rosado/Rosado-CPE-322/blob/main/Labs/Lab3/julian2timeexample.png" width="800" height="600">

```
$ python3 sun.py 'New York'
$ python3 moon.py
```
<img src="https://github.com/Diana-Rosado/Rosado-CPE-322/blob/main/Labs/Lab3/NewYork2moon.png" width="500" height="500">

For the code below, I came across this error:
```
SSLCertVerificationError - Geopy - unable to get local issuer certificate 
```
The reason for this is because after downloading ```brew install python3```, Brew did not run the ```Install Certificates.command``` script that comes in the Python3 bundle for Mac. Run the script that is located under your Applications > Python 3.1.1.

[Stack Overflow Solution](https://stackoverflow.com/questions/44649449/brew-installation-of-python-3-6-1-ssl-certificate-verify-failed-certificate/44649450#44649450)

```
$ python3 coordinates.py 'SC Williams Library'
$ python3 address.py '40.74480675, -74.02532862031404'
```
<img src="https://github.com/Diana-Rosado/Rosado-CPE-322/blob/main/Labs/Lab3/coordinates2address.png" width="1000" height="200">

```
$ python3 cpu.py
$ python3 battery.py
$ python3 documentstats.py document.txt

```
<img src="https://github.com/Diana-Rosado/Rosado-CPE-322/blob/main/Labs/Lab3/cpu2document.png" width="800" height="400">



