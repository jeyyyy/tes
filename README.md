<?xml version='1.0' encoding='utf-8'?>
<widget 
	id="id.desa.muktisari" 
	version="1.0.16" 
	xmlns="http://www.w3.org/ns/widgets" 
	xmlns:gap="http://phonegap.com/ns/1.0">
	
    <name>Desa Muktisari</name>
    <description>
        Kabar terkini dari Desa Muktisari, Kec. Gandrungmangu, Cilacap Barat, Jawa Tengah.
    </description>
    <author email="mail@samsul.web.id" href="http://muktisarigdm.desa.id">
        Samsul Ma'arif
    </author>
    
	<gap:platforms>
		<gap:platform name="android" minVersion="2.2" />
	</gap:platforms>
    
    <preference name="permissions" 					value="none" />
    <preference name="phonegap-version" 			value="3.5.0" />
    <preference name="orientation" 					value="default" />
    <preference name="target-device" 				value="universal" />
    <preference name="fullscreen" 					value="false" />
    <preference name="webviewbounce" 				value="true" />
    <preference name="prerendered-icon" 			value="true" />
    <preference name="stay-in-webview" 				value="true" />
    <preference name="detect-data-types" 			value="true" />
    <preference name="exit-on-suspend" 				value="false" />
    <preference name="show-splash-screen-spinner" 	value="true" />
    <preference name="disable-cursor" 				value="false" />
    <preference name="android-minSdkVersion" 		value="7" />
    <preference name="android-installLocation" 		value="auto" />
    
    <preference name="AutoHideSplashScreen" 		value="true" />
    <preference name="SplashScreen" 				value="screen" />
	<preference name="SplashScreenDelay" 			value="5310" />

	<gap:plugin name="nl.x-services.plugins.socialsharing" 		version="4.3.6" />
	<gap:plugin name="org.apache.cordova.dialogs" 				version="0.2.10" />
	<gap:plugin name="org.apache.cordova.globalization" 		version="0.3.1" />
	<gap:plugin name="org.apache.cordova.inappbrowser" 			version="0.5.2" />
	<gap:plugin name="org.apache.cordova.network-information" 	version="0.2.12" />
	<gap:plugin name="org.apache.cordova.splashscreen" 			version="0.3.3" />

    
    <icon src="res/icon/android/icon-36-ldpi.png" gap:role="default" />
    
    <icon gap:platform="android" gap:qualifier="ldpi" 	src="res/icon/android/icon-36-ldpi.png" />
    <icon gap:platform="android" gap:qualifier="mdpi" 	src="res/icon/android/icon-48-mdpi.png" />
    <icon gap:platform="android" gap:qualifier="hdpi" 	src="res/icon/android/icon-72-hdpi.png" />
    <icon gap:platform="android" gap:qualifier="xhdpi" 	src="res/icon/android/icon-96-xhdpi.png" />
    
    <gap:splash src="icon.png" />
    <gap:splash gap:platform="android" gap:qualifier="ldpi" src="res/screen/android/screen-ldpi-portrait.png" />
    <gap:splash gap:platform="android" gap:qualifier="mdpi" src="res/screen/android/screen-mdpi-portrait.png" />
    <gap:splash gap:platform="android" gap:qualifier="hdpi" src="res/screen/android/screen-hdpi-portrait.png" />
    <gap:splash gap:platform="android" gap:qualifier="xhdpi" src="res/screen/android/screen-xhdpi-portrait.png" />
    <access origin="*" />
</widget>
