## Lab 9

I pledge my honor that I have abided by the Stevens Honor System - Diana Rosado

### YANG

After running these lines of code in the terminal:

```
$ sudo pip3 install pyang plantuml
$ mkdir ~/demo
$ cp ~/iot/lesson9/intrusiondetection.yang ~/demo
$ cd ~/demo
$ cat intrusiondetection.yang
$ pyang -f yin -o intrusiondetection.yin intrusiondetection.yang
$ cat intrusiondetection.yin
$ pyang -f uml -o intrusiondetection.uml intrusiondetection.yang --uml-no=stereotypes,annotation,typedef
$ cat intrusiondetection.uml
$ python3 -m plantuml intrusiondetection.uml
```
Intrusiondetection.yin and intrusiondetection.uml was generated
After running PlantUML, intrusiondetection.png was generated

<img src="https://github.com/Diana-Rosado/Rosado-CPE-322/blob/main/Labs/Lab9/intrusiondetection.png" width="800" height="600">


