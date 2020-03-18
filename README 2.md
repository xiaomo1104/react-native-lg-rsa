
# react-native-lg-rsa

## Getting started

`$ npm install react-native-lg-rsa --save`

### Mostly automatic installation

`$ react-native link react-native-lg-rsa`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-lg-rsa` and add `RNLgRsa.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNLgRsa.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.quenice.cardview.RNLgRsaPackage;` to the imports at the top of the file
  - Add `new RNLgRsaPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-lg-rsa'
  	project(':react-native-lg-rsa').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-lg-rsa/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-lg-rsa')
  	```


## Usage
```javascript
import RNLgRsa from 'react-native-lg-rsa';

// TODO: What to do with the module?
RNLgRsa;
```
  