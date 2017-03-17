# Tutk Kalay Sample code

[![N|Solid](http://www.throughtek.com.tw/images/logo_TUTK.png)](http://www.throughtek.com.tw/kalay_apps.html)

This is a Tutk Kalay APP.

  - P2PCamLive v1.0.0 feature list:
	1. Apply to IOTC_Platform_12w51.
	2. Improve video decode performance.
	3. Wifi password setting with empty word.
	4. App crash in removing camera.
	5. The "Add camera" button is still invisible after removing camera from full list.

---------------------------------------------------------------------------------------

 - P2PCam264 v1.0.0 feature list:
	1. Add G.726 audio codec support.
	2. Fix app crash problem in speaking function with speex codec.
	3. Fix database error in removing camera.
	4. Improve font clarity in Android 3.0 (and above).	
	5. Improve connection speed.
	6. Using system built-in gallery app to open camera album.
	7. Fix multi-channel status detection error.
	8. Fix wrong buffer size error in encoding audio data for sending audio data.

 -  P2PCam264 v0.2.0.5 feature list:

	1. Update IOTCAPIs (1.6.0.1) and AVAPIs (1.2.7.1)

	2. Listening and speaking function in live view page CAN NOT open simultaneously now.

	3. Modify device firmware version in advanced setting page.

	4. Fix CAN NOT playback the last event in the event list page.	

	5. Fix bugs on opening notified events in notification bar.	

	6. Fix list event bug.	

	7. Fix bugs which occurs on rotating device in Android 4.	

	8. Fix bugs which audio in/out switchable with device which without audio in/out function.	

	9. Fix minor bugs.

 - P2PCam264 v0.2.0.4 feature list:

	1. Fix lost frame in channel 0 with multi-stream function.

 - P2PCam264 v0.2.0.3 feature list:

	1. Fix text encoding error in device info and wifi list.

 - P2PCam264 v0.2.0.2 feature list:

	1. Fix crash in event searching in v0.2.0.1

 - P2PCam264 v0.2.0.1 feature list:

	1. Fix wrong icon in main page

	2. Fix no snapshot refresh on camera list when back from liveview page

	3. Fix no add button appearing after removing cameras

	4. Fix LAN Search bug in Android 4.0

 - P2PCam264 v0.2.0.0 feature list:

	1. New UI

	2. Add ADPCM Support

	3. Add Multi-Channel support

	4. Add 720P resolution support

	5. Minor bug fix

# HOW TO BUILD THIS PROJECT!

 1. Git clone ActionBarSherlock and IOTCamera_Android from bitbucket.
2. Link ActionBarSherlockLibrary as library to your project.
3. Link IOTCamera as library to your project.
4. Copy libs(from SDK release package) to libs/armeabi/
5. In eclipse, using Window -> Preferences -> Android -> Build -> uncheck "Force error when external jars contain native libraries"
