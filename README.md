# react-native-custom-icon

## Getting started

`$ npm install https://github.com/jinyaoye23/react-native-custom-icon.git --save`

### Mostly automatic installation

`$ react-native link react-native-custom-icon`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-custom-icon` and add `CustomIcon.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libCustomIcon.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### iOS 更换图标配置[请参考](https://juejin.im/post/59395f9761ff4b006c6c204e)
##### 1.配置图标

##### 2.info.plist配置


#### Android

1. Open up `android/app/src/main/java/[...]/MainApplication.java`
  - Add `import com.reactlibrary.CustomIconPackage;` to the imports at the top of the file
  - Add `new CustomIconPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-custom-icon'
  	project(':react-native-custom-icon').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-custom-icon/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-custom-icon')
  	```


## Usage
```javascript
import CustomIcon from 'react-native-custom-icon';

// TODO: What to do with the module?
CustomIcon;
```
