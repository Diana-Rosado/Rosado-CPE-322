## Lab 4

I pledge my honor that I have abided by the Stevens Honor System - Diana Rosado


For this lab, I used Django, Django REST, and raspberrypi v4 to display a weather app, cpu specs, and hello world.

### 1. Install Django and Django REST framework on Raspberry Pi

```
$ pip3 -V
$ pip3 list
$ sudo pip3 install -U setuptools
$ sudo pip3 install -U django
$ sudo pip3 install -U djangorestframework
$ sudo pip3 install -U django-filter
$ sudo pip3 install -U markdown
$ sudo pip3 install -U requests
```

### 2. Install MariaDB server and client on Raspberry Pi


```
$ sudo apt update
$ sudo apt install mariadb-server mariadb-client
$ sudo apt install python3-mysqldb
$ sudo pip3 install -U mysqlclient
$ sudo mysql_secure_installation
Enter current password for root (enter for none): 
Change the root password? [Y/n] 
New password: PASSWORD
Re-enter new password: PASSWORD
Remove anonymous users? [Y/n] 
Disallow root login remotely? [Y/n] 
Remove test database and access to it? [Y/n] 
Reload privilege tables now? [Y/n]
```

### 3. Start the Django project stevens
```
pi@raspberrypi:~ $ django-admin startproject stevens
pi@raspberrypi:~ $ cd stevens
pi@raspberrypi:~/stevens $ ls
manage.py  stevens

pi@raspberrypi:~/stevens $ python3 manage.py startapp myapp
pi@raspberrypi:~/stevens $ ls
manage.py  myapp  stevens
```

After following the steps on https://github.com/kevinwlu/iot/tree/master/lesson4/stevens. I produced the following image on my TV at the url: http://127.0.0.1:8000


<img src="https://github.com/Diana-Rosado/Rosado-CPE-322/blob/main/Labs/Lab4/weather.jpeg" width="800" height="600">

After, I opened a laptop browser and visited the Raspbbery PI IP address as oppposed to the local host.

<img src="https://github.com/Diana-Rosado/Rosado-CPE-322/blob/main/Labs/Lab4/django%20stevens.png" width="800" height="600">

### 3. Start the Django REST project mycpu
After following the steps on https://github.com/kevinwlu/iot/tree/master/lesson4/mycpu I produced the following image on my TV at the url: http://127.0.0.1:8000


<img src="https://github.com/Diana-Rosado/Rosado-CPE-322/blob/main/Labs/Lab4/mycpu.jpeg" width="800" height="600">


### 4.  Run Flask server and open a browser via VNC Viewer and go to http://127.0.0.1:5000/

<img src="https://github.com/Diana-Rosado/Rosado-CPE-322/blob/main/Labs/Lab4/hello%20world.jpg" width="800" height="400">

