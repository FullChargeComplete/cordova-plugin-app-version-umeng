#  ionic获取友盟渠道插件
插件改自https://github.com/whiteoctober/cordova-plugin-app-version，主要是为了获取友盟统计的渠道号
更改了获取包名的方法 安装和官网一样 
```
ionic cordova plugin add https://github.com/ZhuSiSheng/cordova-plugin-app-version-umeng

npm install --save @ionic-native/app-version@4

this.appVersion.getPackageName().then(val=>{
    alert(val)
})
```
