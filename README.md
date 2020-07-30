![react-native-bridge](https://luokun.oss-cn-hangzhou.aliyuncs.com/github/react-native-limitations-best-practices-to-deal-with-them.png)
> 一个含个人倾向的react-native高级拓展开发文档！

## 简介
 - [文档简介](https://github.com/React-Sextant/react-native-bridge-docs/wiki/文档简介)

## 文档
 - [Easing](https://github.com/React-Sextant/react-native-bridge-docs/issues/2)
 - [StyleSheet](https://github.com/React-Sextant/react-native-bridge-docs/issues/3)
 - [Color](https://github.com/React-Sextant/react-native-bridge-docs/issues/4)
 - [DeviceEventEmitter](https://github.com/React-Sextant/react-native-bridge-docs/issues/5)
 - [NativeEventEmitter](https://github.com/React-Sextant/react-native-bridge-docs/issues/5)
 - [findNodeHandle](https://github.com/React-Sextant/react-native-bridge-docs/issues/6)

## Android源码目录
#### com.facebook.react.*
 - uimanager
   - [SimpleViewManager](https://github.com/React-Sextant/react-native-bridge-docs/wiki/SimpleViewManager)
   - [ViewGroupManager](https://github.com/React-Sextant/react-native-bridge-docs/wiki/ViewGroupManager)
 - bridge
   - [ReactContext](https://github.com/React-Sextant/react-native-bridge-docs/wiki/ReactContext)
   - [ReactContextBaseJavaModule](https://github.com/React-Sextant/react-native-bridge-docs/wiki/ReactContextBaseJavaModule)
 - [ReactActivity](https://github.com/React-Sextant/react-native-bridge-docs/wiki/ReactActivity)
 - [ReactActivityDelegate](https://github.com/React-Sextant/react-native-bridge-docs/wiki/ReactActivityDelegate)
 
## 踩坑实录

 1. [FileProvider在React Native中的执行时机](https://github.com/React-Sextant/react-native-bridge-docs/issues/1)
