#Appium


####Appium is an open-source tool used for automating native, web and hybrid applications on iOS and Android platforms.
	It also allows us to run the automated tests on actual devices, emulators and simulators.
	It is mainly used for mobile test automation at GUI level
	It is traditionally considered a "black box" testing tool, which means it doesnot have access to your application's internal state or method. 
	But off late,thanks to Appium's Espresso driver, white box testing is also possible now.
	The tool can be used for functional testing of the apps 


##Features

#### *Appium supports cross-platform testing, which is, if you have the same app running on both Android and iOS, Appium can be used to run tests on both platform with minimal or no code changes. This allows reuse of code.
	 *It supports major programming languages: Java, Python, Ruby, C#, etc.
	 *It supports Selenium Webdriver API, so you don’t have to learn anything new, presuming you are already familiar with Selenium
	 *It supports  hybrid or web testing. It uses WebDRiver protocol, which can be used to switch between native app and web content.
	 *It’s an open source tool and has a broad community
	 
	 
##Pros

#### *Appium supports Android and iOS platforms
	 *Appium doesn’t require any in-app modifications for testing. An application can be tested right after it’s been downloaded and installed on the device.
     *This tool allows automating web, native and hybrid applications, while also offering support for various hardware actions
	 *Sauce labs, guys in charge of Appium, specify in creating various well-known open source automation and manual testing solutions. As a result, Appium is frequently updated and each new release includes new useful features and bug fixes.
	 
##Cons

#### *Appium doesn’t support image recognition
	 *Few hardware actions like swipe, gestures work only on native application.
	 *iOS tests cannot be executed in parallel
	 *Time taken to get Appium up and running is long
	 
	 
##Required information / models

####Appium is an 'HTTP Server' written using a Node.js platform and drives iOS and an Android session using Webdriver JSON wire protocol.
	So,before initializing the Appium Server, Node.js must be pre-installed on the system.
	
	
##Target platform and dependencies

####Appium is used to automated mobile apps- both native and web. It supports many languages like Java, C#, Python.

##Dependencies

####*Install ANDROID SDK (Studio) [Link] (https://developer.android.com/studio)
	*Install JDK (Java Development Kit) [Link] (https://www.guru99.com/install-java.html)
	*Install Eclipse [Link] (https://www.eclipse.org/downloads/)
	*Install TestNg for Eclipse [Link] (https://www.guru99.com/all-about-testng-and-selenium.html#1) 
	*Install Selenium Server JAR [Link] (https://www.guru99.com/introduction-to-selenium-grid.html#1)
	*Appium Client Library [Link] (http://appium.io/docs/en/about-appium/appium-clients/index.html)
	*APK App Info on Google Play [Link] (https://play.google.com/store/apps/details?id=de.migali.soft.apkinfo&hl=en) 
	*js (Not Required - Whenever Appium server is installed, it by default comes with "Node.exe" & NPM. It's included in Current version of Appium.)
	*Install Appium Desktop

	
##Updates

####Sauce labs and Open source community keeps the tool updated with regular updates.(You get stable updates once in two to three weeks)

##Latest update: 1.12.1 , 1-04-2019
##First release date: 1.0, May 2014

##Licensing / Cost
####Its an open spource tool, which can be used free of charge.


##Tutorials and documentation

####The links to how to start with appium is [Link] (http://appium.io/docs/en/about-appium/intro/)


##Usage examples

####Appium has been used by various softwares, which provide wrapper and include other features. 
	Appium makes the job of application testing easy and effective.
	Few mobile testing automation tools that currently support Appium include Katalon, Appium Studio, Oxygen, and TestProject.
	These tools are there to help you simplify the way you build Appium tests.

	
##Alternative tools

####*[Robotium] (https://github.com/RobotiumTech/robotium)
	*[Calabash] (https://calaba.sh/)
	*[XCTest] (https://developer.apple.com/documentation/xctest)
