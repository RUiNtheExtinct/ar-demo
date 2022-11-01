<!-- @format -->

## <!-- @format -->

---

# AR using React Native

---

## There are 3 primary options for implementing AR natively i.e., with ARKit/ARCore support in React Native:

### 1. [viro-react](https://github.com/ViroCommunity/starter-kit)

-   ViroReact is a React Native library for building AR/VR applications.
-   It is built on top of React Native and exposes a declarative API for creating AR/VR applications.
-   ViroReact is a cross-platform framework that supports both iOS and Android.
-   **The steps to implement Viro in your project is given in the link above.**
-   [An intoduction to ViroReact](https://medium.com/simform-engineering/what-is-augmented-reality-how-to-implement-ar-using-react-native-2340bdba9a8d)
-   Advantages:
    -   Easy to use
    -   Supports both 2D and 3D
    -   Supports both iOS and Android
    -   Supports both WebGL and Canvas
    -   Supports both Expo and React Native CLI
-   Disadvantages:
    -   Poorer performance than BabylonJS
-   [Documentation](https://docs.viromedia.com/docs/quick-start)
-   Examples
    -   [Simple Example](https://blog.expo.dev/introducing-expo-ar-mobile-augmented-reality-with-javascript-powered-by-arkit-b0d5a02ff23)
    -   [Samples](https://github.com/ViroCommunity/samples)

### 2. [babylon-react-native](https://github.com/BabylonJS/BabylonNative)

-   Babylon React Native is a React Native library for building AR/VR applications extending the BabylonJS framework.
-   It brings the power of BabylonJS to React Native.
-   Babylon React Native is a cross-platform framework that supports both iOS and Android.
-   **The base BabylonJS package has support for XR built into it so for implementing AR, you don't need to install any additional packages.**
-   Advantages:
    -   Supports both 2D and 3D
    -   Supports both iOS and Android
    -   Supports both WebGL and Canvas
    -   More functionality offer as comapared to Viro
-   Disadvantages:
    -   No support for Expo
-   [Documentation](https://doc.babylonjs.com/features/featuresDeepDive/webXR/webXRARFeatures)
-   [Extensions for XR in Babylon React Native](https://github.com/zappar-xr/zappar-babylonjs)
-   Examples
    -   [Putting a mesh in space](https://playground.babylonjs.com/#KDWCZY)
    -   [XR Measuring Tape](https://playground.babylonjs.com/#GG06BQ#97)

### 3. [expo-three](https://github.com/expo/expo-three)

-   Expo-three is a React Native library for building AR/VR applications extending the ThreeJS framework.
-   It is simply a wrapper around the base ThreeJS package for React Native.
-   **The steps to implement ExpoThree in your project is given in the link above.**
-   Advantages:
    -   Easy to use
    -   Supports both 2D and 3D
    -   Supports both WebGL and Canvas
    -   Supports both Expo and React Native CLI
-   Disadvantages:
    -   Limited to Expo
    -   No ARCore support for Android
-   [Documentation for Expo](https://docs.expo.io/versions/latest/sdk/gl-view/)
-   [Documentation for ExpoThree](https://docs.expo.io/versions/latest/sdk/gl-view/)
-   [Examples](https://blog.expo.dev/introducing-expo-ar-mobile-augmented-reality-with-javascript-powered-by-arkit-b0d5a02ff23)

---

# WebXR using React Native

---

## Primary options for implementing WebXR in React Native are:

### 1. [react-three-fiber](https://github.com/pmndrs/react-three-fiber)

-   React-Three-Fiber is a wrapper for building 3D applications extending the ThreeJS framework in a React-like declarative format
-   It is built on top of React Native and exposes a declarative for for creating AR/VR applications.
-   It offers better performance as compared to expo-three
-   react-three-fiber can be implpemented as a base template for your project with the following command:

```bash
	npx rcreate-react-native-app -t with-react-three-fiber <project-name>
```

-   **The steps to implement React Three Fiber in a more granular manner in your project is given in the link above.**
-   [WebXR Extension for react-three-fiber](https://github.com/pmndrs/react-xr)
-   Advantages:
    -   Easy to use
    -   Supports both 2D and 3D
    -   Supports both iOS and Android
    -   Supports both WebGL and Canvas
    -   Supports both Expo and React Native CLI
-   Disadvantages:
    -   No support for ARCore in Android
-   [Documentation](https://docs.pmnd.rs/react-three-fiber/getting-started/introduction)
-   Examples
    -   [Samples](https://codesandbox.io/examples/package/@react-three/xr)

### 2. [babylon-react-native](https://github.com/BabylonJS/BabylonNative)

-   Babylon React Native is a React Native library for building AR/VR applications extending the BabylonJS framework.
-   It brings the power of BabylonJS to React Native.
-   The method for implementing XR is similar to that of **AR** in **babylon-react-native**.
-   **The base BabylonJS package has support for XR built into it so for implementing AR, you don't need to install any additional packages.**
-   Advantages:
    -   Supports both 2D and 3D
    -   Supports both iOS and Android
    -   Supports both WebGL and Canvas
    -   More functionality offer as comapared to Viro
-   Disadvantages:
    -   No support for Expo
-   [Documentation](https://doc.babylonjs.com/features/featuresDeepDive/webXR/webXRARFeatures)
-   [Extensions for XR in Babylon React Native](https://github.com/zappar-xr/zappar-babylonjs)
-   Examples
    -   [Putting a mesh in space](https://playground.babylonjs.com/#KDWCZY)
    -   [XR Measuring Tape](https://playground.babylonjs.com/#GG06BQ#97)

### 3. [expo-three](https://github.com/expo/expo-three)

-   Expo-three is a React Native library for building AR/VR applications extending the ThreeJS framework.
-   It is simply a wrapper around the base ThreeJS package for React Native.
-   The method for implementing XR is similar to that of **AR** in **expo-three**.
-   **The steps to implement ExpoThree in your project is given in the link above.**
-   Advantages:
    -   Easy to use
    -   Supports both 2D and 3D
    -   Supports both WebGL and Canvas
    -   Supports both Expo and React Native CLI
-   Disadvantages:
    -   Limited to Expo
    -   No ARCore support for Android
-   [Documentation for Expo](https://docs.expo.io/versions/latest/sdk/gl-view/)
-   [Documentation for ExpoThree](https://docs.expo.io/versions/latest/sdk/gl-view/)
-   [Examples](https://blog.expo.dev/introducing-expo-ar-mobile-augmented-reality-with-javascript-powered-by-arkit-b0d5a02ff23)
