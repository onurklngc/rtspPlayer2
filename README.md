# rtspPlayer2
RTSPBasic


cordova create edimax
 
cd edimax
 
cordova platform add ios --save
 
cordova plugin add https://github.com/Onurklngc/edimaxCamPlugin.git

cordova plugin add https://github.com/Onurklngc/rtspPlayer2.git
 
cordova build ios
 
cordova run ios
 
cordova plugin rm com.madtatu.rtspPlayer