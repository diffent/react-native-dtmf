
# react-native-dtmf

        WIP: Not yet working

## Getting started

`$ npm install react-native-dtmf --save`

### Mostly automatic installation

`$ react-native link react-native-dtmf`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-dtmf` and add `RNDtmf.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNDtmf.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNDtmfPackage;` to the imports at the top of the file
  - Add `new RNDtmfPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-dtmf'
  	project(':react-native-dtmf').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-dtmf/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-dtmf')
  	```

## Usage
```javascript
import RNDtmf from 'react-native-dtmf';

// TODO: What to do with the module?
RNDtmf;
```
  