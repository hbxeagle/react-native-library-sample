
# react-native-library-sample

## Getting started

`$ npm install react-native-library-sample --save`

### Mostly automatic installation

`$ react-native link react-native-library-sample`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-library-sample` and add `RNLibrarySample.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNLibrarySample.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNLibrarySamplePackage;` to the imports at the top of the file
  - Add `new RNLibrarySamplePackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-library-sample'
  	project(':react-native-library-sample').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-library-sample/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-library-sample')
  	```


## Usage
```javascript
import RNLibrarySample from 'react-native-library-sample';

// TODO: What to do with the module?
RNLibrarySample;
```
  