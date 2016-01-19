# ionicDev
使用ionic开发工程时调试方式

## iOS模拟
1. sudo npm i -g ios-sim
2. ionic platform add ios
3. ionic build ios
4. ionic emulate ios

## Android模拟
1. 采用genymotion，使用virtual box虚拟机进行构建ADT（genymotion V2.6，virtual box V4.3.28）
2. 针对genymotion设置proxy，http：1.234.45.50:3128
3. ionic platform add android
4. ionic build android
5. ionic run android

## 注意事项
1. 针对android项目构建时，可能需要手动更改sdk version，应在android工程下修改两处文件： project.properties & CordovaLib/project.properties
