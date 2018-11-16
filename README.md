# How to
1. Install build dependencies and setup environment (android sdk, npm, yarn, react-native etc.)
2. Clone repository
3. ```yarn install --pure-lockfile```
4. Adjust count.ly parameters in App.js
5. ```cd android & ./gradlew assembleRelease```
6. ```adb install -r ./app/build/outputs/apk/release/app-release.apk```
