# cordova-bug

# Exploit Title: 
information disclosure  in [cordova - mobile]
# Date: 
30/06/2023
# Exploit Author: 
Xcode0x (Mohamed Almarri)
# Vendor Homepage: 
https://cordova.apache.org/
# Software Link: 
https://cordova.apache.org/#getstarted
# Version: 
all
# Tested on: 
IOS & Android 
----
####  information disclosure  :
Just unzip android Or IOS app and will see leak api or source code for api in applications .
#### POC [IOS]:
after unzip IOS ipa it will be in this file :
1- cd /home/user/Desktop/Payload/App.app/public

2- leak source code and sensitive information will be in "main.js" such as :

* api path 

* sensitive information  for users or admin

and more ....

it Depends on the application and how it was developed .
