# AngularCordova

refer to this link [medium-blog](https://medium.com/@abayomismart/creating-android-ios-app-with-cordova-and-angular-e3cf82d4cbc2)

# Project setUp  
1. installing of the cordova globally 
2. When the installation is completed. Go to the root directory of the angular application and run this command below to create your cordova application.

    `cordova create angular_cordova com.angular_cordova angular_cordova`
3. after above command file will be generated which contains the config.xml  
4. move the config.xml to the root folder of the angular project. 
5. add the following in package.json in you angular root file. 

     ``  "cordova-plugin-whitelist": "1.3.4"
  "}",
  "cordova": {
    "plugins": {
      "cordova-plugin-whitelist": {}
    },
    "platforms": [
      "android",
      "browser"
    ]
  }
     ``
