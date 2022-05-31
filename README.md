# react-nested-navigation
react navigation nested with Stack, Tab and Drawer
#Combining Stack, Tab & Drawer Navigations in React Native With React Navigation 5

#PROJECT SETUP

npm install -g expo-cli

#CREATE A PROJECT

expo init react-nested-navigator

#INSTALL DEPENDENCIES

npm install @react-navigation/native @react-navigation/stack @react-navigation/bottom-tabs @react-navigation/drawer

npm install react-native-reanimated react-native-gesture-handler react-native-screens react-native-safe-area-context @react-native-community/masked-view

#INSTALL PLUGIN

expo install react-native-reanimated

#ADD BABEL PLUGIN IN BABEL.CONFIG.JS

module.exports = function(api) {
  api.cache(true);
  return {
    presets: ['babel-preset-expo'],
    plugins: ['react-native-reanimated/plugin'],
  };
};

#LAST IMPORTANT STEP

After you add the Babel plugin, restart your development server and clear the bundler cache: 

expo start --clear

#end
