# React Native

# Dive Right in
a. Introduction - Course Roadmaps</br> 
    - Setup Enviroment</br>
b. Roadmap to the first App</br> 
    - Setup Dependecies berdasarkan Oprating System</br> 
    - Install ESLint</br> 
    - Genrate React Native App</br>

# Got OSX Go Here</br>
a. OSX Installation</br>
b. More on OSX Installation</br>
c. Running in the Simulator</br>

# Got Windows Go Here</br>
a. Windows Setup of React Native</br> 
    - Install Java JDK (1.8)</br> 
    - Node JS (For Genrate Bundle, Package Management)</br> 
    - Android Studio (SDK Management)</br>
b. Android Studio and React Native CLI Installation</br> 
    - Sediakan lokasi install Android Studio dan lokasi Android Sdk</br> 
    - Install React Native CLI npm install -g react-native-cli</br> 
    - Create React Native Project react-native init albums</br> 
c. Emulator Creation and System Variables</br> 
    - Download Android SDK - Buat Android Emulator </br> 
    - Setting Enviroment variable (JAVA_HOME, path, dll)</br> 
    - Jalankan Emulator react-native run-android</br> 
    - Doubel R to reaload simulator</br> 
    - Ctrl + M = Untuk membuka menu pada simulator</br> 
    
# ESLint Setup</br> 
 a. Download Visual Studio Code</br> 
 Install Plugin ESLint, Material Icon Theme, Prettier</br> 

# Onwards!</br> 
a.  Project Directory Walkthrough </br> 
Secara otomatis akan create Opration System dependencies android dan ios, ada juga node_modules, ini adalah module yang sifatnya global atau plugin yang app gunakan. Index.js starting point aplikasi kita.</br>
b. Getting Content on the Screen </br>
    - Setiap menampilkan data harus menggunakan component</br>
```
// Import a Libraray to help create component
import React from "react";
import ReactNative from "react-native";

// Create Component

// Render it to the device
```
c. React vs React Native </br> 
React : Cara kerja masing2 component, cara integrasi antar component</br>
ReactNative : Bridge ke mobile device, component dan rendernya</br>
React Native mengacu pada ES6, dimana tidak ada file yang bisa di access secara global, tetapi dengan menggunakan import.

d. Creating a Component with JSX</br>
JSX Html alike. Unutk membuat starting component kita akan membuat suatu function yang render jsx. Kenapa menggunakan layaknya html ? untuk memudahkan developer dalam pengambangan ui</br>
Babel (bebeljs.io) : Adalah tool/framework yang akan mengubah jsx menjadi pure javascript
```
<Text>Some Text</Text>

React.createElement(Text, null, "Some Text")
```
```
// Import a Libraray to help create component
import React from "react";
import ReactNative from "react-native";

// Create Component
const App = () => {
  return <Text>Some Text</Text>;
};

// Render it to the device
```
