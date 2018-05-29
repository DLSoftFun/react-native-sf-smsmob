# react-native-sf-mob
  * npm i react-native-sf-mob
  * react-native link react-native-sf-mob
  * 添加lib库 
  * ![1](https://github.com/DLSoftFun/react-native-sf-smsmob/blob/master/1.png)
  * infoplist 添加key `MOBAppKey`  `MOBAppSecret` 添加你在mob注册的appkey和secret
  
# 使用 
 ```
 var SFSMS = NativeModules.SFSMS;
 //接收验证码
 SFSMS.getSMSCode('18641575390', (data) =>{

 })
 //校验
 SFSMS.submitCode('18641575390' 'code!!!!!!!', (data) =>{

 })
 ```
