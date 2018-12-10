# Expo-graphics-Simple-Example
A actually working expo-graphics example

To get the expo-graphics working, I have to use a specific version of `expo-graphics` plus a specific version of `expo`. That is v1.0.0-alpha.1 for `expo-graphics` and v28 for `expo`.  

To start the project:
```
npm install
expo start
```
  
I found that `expo-graphics` DOES NOT work with the current expo sdk v31. Upgrading expo-three, three, and expo-graphics are just a hot mess that you should not avoid. Incompatibility and missing dependency will make you suffer. I experience that. It is not a good one. It makes me feel expo is just not stable enough for production usage. 

I mainly test on Android Pie.


It will throw error if you use the latest version of `expo` and `expo-graphics`. 
```
undefined is not an object (evaluating'_expo.AR.TrackingConfigurations.World')
```
You can experience the frustration if you checkout the branch `sdk_31`.
