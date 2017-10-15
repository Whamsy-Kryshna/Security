 # NATAS
This file contains my solutions to **Natas** wargame from http://overthewire.org
## Level-0
Go to the url : http://natas0.natas.labs.overthewire.org and login with:
* ID: natas0
* Pwd: natas0
## Level 0-1
After logging in using the ID and Pwd from level-0, right click on the page and click on view source <br />
You will find something like : <--The password for natas1 is gtVrDuiDfck831PqWsLEZy5gyDz1clto --> <br />
Go to the url : http://natas1.natas.labs.overthewire.org and login with:
* ID: natas1
* Pwd: gtVrDuiDfck831PqWsLEZy5gyDz1clto
## Level 1-2
After logging into level-1 open developer options using menu on browser or click F12<br />
You will see something like : <--The password for natas2 is ZluruAthQk7Q2MqmDeTiUij2ZvWy2mBi --> <br />
Go to the url : http://natas2.natas.labs.overthewire.org and login with:
* ID: natas2
* Pwd: ZluruAthQk7Q2MqmDeTiUij2ZvWy2mBi
## Level 2-3
After logging into Level-2, view page source and in the main div: content, we can see an image with fiel path : files/pixel.png <br />
Go to the url and add /files at the end of url. We can see that the parent directory has two files and users.txt has the password we need <br />
Go to the url : http://natas3.natas.labs.overthewire.org and login with:
* ID: natas3
* Pwd: sJIJNW6ucpu6HPZ1ZAchaDtwd7oGrD14
## Level 3-4
After logging into level 3, we see something like <-- No more information leaks!! Not even Google will find it this time... --> in the page source view. This hints something at google's crawler which is robots.txt <br />
Go to http://natas3.natas.labs.overthewire.org/robots.txt<br />
We see something like : Disallow: /s3cr3t/ <br />
Now go to http://natas3.natas.labs.overthewire.org/s3cr3t/<br />
We can see that the password is in users.txt file 
* ID: natas4
* Pwd: Z9tkRkWmpt9Qr7XrR5jWRkgOU901swEZ
