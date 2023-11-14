# Requirements
* Node.js 18
* JAVA 21 (maybe it work with 17/18)
* We use NDK 23 which has both M1 support and is the side-by-side NDK 
  * ndkVersion "23.1.7779620" version from AGP.  

# Steps

1. `git clone https://git.gaf.de/MCarvalho/nodejs-mobile-reactnative`
2. `npm i && cd nodejs-assets/nodejs-project && npm i`
3. Try to build with `npm run android` 
4. Create the android folder with `npx expo run:android`
5. Run, again, the following `npx expo run:android` or run if from Android Studio
