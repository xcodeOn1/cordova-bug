# cordova information disclosure
# Version: 
all
# Tested on: 
IOS & Android 
----
# information disclosure  :
Just unzip android Or IOS app and will see leak api or source code for api in applications .
# POC [IOS]:
after unzip IOS ipa it will be in this file :

1- cd /home/user/Desktop/Payload/AppName.app/public

2- leak source code and sensitive information will be in "main.js"  such as :

* api path 

* sensitive information  for users or admin

and more ....

As a developer, you should be aware when using Cordova. Read this for more information:
https://cordova.apache.org/docs/en/11.x/guide/appdev/security/index.html#do-not-assume-that-your-source-code-is-secure

## Nuclei Template  :

i made template for that after you unzip the "ipa" use this command :

echo ~/app_folder | nuclei -t ~/cordova-bug/cordova-data.yaml

 ![Script](https://github.com/xcodeOn1/cordova-bug/blob/main/poc.png)

 ![Script](https://github.com/xcodeOn1/cordova-bug/blob/main/token.png)

 # Tested 

 test in many apps even if android or IOS .
