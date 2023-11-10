# Requirements
Node.js 18

JAVA 21 (maybe it work with 17/18)

// We use NDK 23 which has both M1 support and is the side-by-side NDK version from AGP.
ndkVersion = "23.1.7779620"

# Steps

1. `git clone https://git.gaf.de/MCarvalho/nodejs-mobile-reactnative`
2. `npm i && cd nodejs-assets/nodejs-project && npm i`
3. Try to build with `npm run android` 
4. Create the android folder with `npx expo run:android`
5. Let's force to build sqlite3 from the source. For this go to `nodejs-assets/nodejs-project/node_modules/sqlite3/package.json` and change the script *install* to `npm install --build-from-source`.

# Resources

https://reactnative.dev/docs/environment-setup  
https://stackoverflow.com/questions/44270504/react-native-ios-and-android-folders-not-present  