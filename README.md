
# react-native-circle-image

## Getting started

`$ npm install react-native-circle-image --save`

### Mostly automatic installation

`$ react-native link react-native-circle-image`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-circle-image` and add `RNCircleImage.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNCircleImage.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNCircleImagePackage;` to the imports at the top of the file
  - Add `new RNCircleImagePackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-circle-image'
  	project(':react-native-circle-image').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-circle-image/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-circle-image')
  	```

#### Windows
[Read it! :D](https://github.com/ReactWindows/react-native)

1. In Visual Studio add the `RNCircleImage.sln` in `node_modules/react-native-circle-image/windows/RNCircleImage.sln` folder to their solution, reference from their app.
2. Open up your `MainPage.cs` app
  - Add `using Circle.Image.RNCircleImage;` to the usings at the top of the file
  - Add `new RNCircleImagePackage()` to the `List<IReactPackage>` returned by the `Packages` method


## Usage
```javascript
import RNCircleImage from 'react-native-circle-image';

// TODO: What to do with the module?
RNCircleImage;
```
  