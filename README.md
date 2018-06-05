# OffTraffic-SDK-Android
The official Android SDK for OffTraffic.io

**This is the official OffTraffic.io Android SDK**

In order to download the latest .aar file go here: https://github.com/offtraffic/OffTraffic-SDK-Android/tree/aar/Aar

_Instructions:_
* Import the offtraffic.aar file
* Write in your gradle file


dependencies{
 implementation files('libs/offtraffic.aar')
}

Code:
* _//import the library
* import io.offtraffic.*;
* _//use this function to initialize the sdk_
* OffTraffic.Initialize(getApplicationContext(), publisher_id, placement_id);
* _//use this function to download interstitials locally_
* OffTraffic.downloadInterstitials();
* _//use this function to show an interstitial_
* OffTraffic.showInterstitial();



<img src="http://valiprod.com/offtraffic/screenshots_android/1.png" width="30%" height="30%">
<img src="http://valiprod.com/offtraffic/screenshots_android/2.png" width="30%" height="30%">
<img src="http://valiprod.com/offtraffic/screenshots_android/3.png" width="30%" height="30%">
<img src="http://valiprod.com/offtraffic/screenshots_android/4.png" width="30%" height="30%">
<img src="http://valiprod.com/offtraffic/screenshots_android/5.png" width="30%" height="30%">
<img src="http://valiprod.com/offtraffic/screenshots_android/6.png" width="30%" height="30%">
<img src="http://valiprod.com/offtraffic/screenshots_android/7.png" width="30%" height="30%">
