cordova-plugin-x5-webview
====

Makes your Cordova application use the Tencent X5 WebView(TBS) instead of the System WebView. Requires cordova-android 4.0 or greater.

Benefits
----

WebView doesn't change depending on Android version
Capabilities: such as WebRTC, WebAudio, Web Components
Performance improvements (compared to older system webviews)

Drawbacks
----

Increased APK size (about 300KB)

Install
----
The following directions are for cordova-cli (most people). Alternatively you can use the Android platform scripts workflow.

Open an existing cordova project, with cordova-android 4.0.0+, and using the latest CLI. X5 variables can be configured as an option when installing the plugin
<br/>Add this plugin   
``$ cordova plugin add cordova-plugin-x5-webview``<br/>  
Build    
``$ cordova build android``

The build script will automatically fetch the X5 WebView libraries from X5 project download site (https://www.npmjs.com/package/cordova-plugin-x5-webview) and build for both X86 and ARM architectures.
