# ionic_login

change 

`<widget id="`**io.ionic.starter**`" version="0.0.1" xmlns="http://www.w3.org/ns/widgets" xmlns:cdv="http://cordova.apache.org/ns/1.0">`

to

`<widget id="`**com.ieeess.slsywc17_mobile_app**`" version="0.0.1" xmlns="http://www.w3.org/ns/widgets" xmlns:cdv="http://cordova.apache.org/ns/1.0">`

---
run 

* `ionic cordova plugin add cordova-plugin-facebook4 --variable APP_ID="142512796409901" --variable APP_NAME="slsywc17-mobile-app"`
* `npm install --save @ionic-native/facebook`
* `ionic cordova platform add android`
* `ionic cordova platform add ios`
* `ionic cordova platform add browser`
* `ionic cordova prepare`
* `ionic cordova run browser -l`
