# screen-capture-poc

To do local desktop screen capture and store as image.

Another way to do similar:

copy imageto clipboard and paste into browser

http://jsfiddle.net/KJW4E/905/


## Pre-requisite
1. install chrome plugin https://chrome.google.com/webstore/detail/screen-capturing/ajhifddimkapgcifgcodmmfdlknahffk
2. only in chrome browser
3. npm install -g http-server for http server hosting

## run
```
cd screen-capture-poc
http-server .
 ```

## Known issue

1. cannot run in remote hosting. only in localhost.

reason:

 need https for remote hosting and need update the getUserMedia method