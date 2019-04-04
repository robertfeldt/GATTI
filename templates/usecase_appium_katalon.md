#Case Study - Katalon tool


## What is the purpose of the sw/lib, i.e. what does it aim to do for users/developers?

####Katalon is a ready-to-use mobile automation framework that supports cross-platform and cross-device mobile and web app testing automation. 
	The tool provides real-time analytics to help identify defects faster and improve testing strategies.
	Its open source tool and is there to make test automation easier and accessible to everyone.
	
	
##What are the key technologies used to develop the lib?

####Built on top of Selenium and Appium, the tool is publicly available to perform automation testing on web and mobile.
	It uses Kobiton’s cloud-based device farm to execute automated tests on real devices. The tool provides real-time analytics to help identify defects faster and improve testing strategies.
	It utilizes Selenium’s Desired Capabilities to work with various browser capabilities that are aligned with user preferences like handling browser cookies and SSL security popup etc.
	
	
##What kind of automated testing tools are used to test the sw/lib (including but possible more than YTT) and what are their key features?

####Katalon uses Selenium and Appium for automation testing.
	Katalon Studio supports web testing, API testing using Selenium 
	It supports mobile testing using Appium.
	
	
##Which features of the automated testing tools are currently used by the test suite?

####It uses object spy feature, which is unique to Appium Studio. This feature allows you to retrieve an XML dump of all the elements that are present on the screen at a given moment. With the dump, you can then generate XPath queries that will then be used in your testing. The object spy also allows you to learn about the nature of each element by presenting you with a full set of that element’s properties.
	It uses appium libraries for native, web app mobile automation.
	
	
##Which features of the automated testing tools are NOT used by the test suite?

####As this tool is built on Appium, all the appium features are supported by Katalon.
	But Katalon mainly prefers or supports Java/Groovy as scripting language, as compared to appium which supports many more languages.