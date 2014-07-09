#Autodesk View and Data API workflow sample for iOS 

The MIT License (MIT)

Copyright (c) 2014 Autodesk, Inc.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


##Description

*This sample is part of the [Developer-Autodesk/Autodesk-View-and-Data-API-Samples](https://github.com/Developer-Autodesk/autodesk-view-and-data-api-samples) repository.*

This sample shows how to use the API to authenticate, upload a file, and start and monitor the translation process which creates a viewable file and its thumbnail.

It has four buttons:
* Log In: use API to get authenticated
* Select File: select a file from the DropBox account on the iOS device and then store it in an NSData object
* Upload to A360: this creates a bucket on A360 and places the file there, then starts the translation process on it
* Check Progress: check how far the translation process got. If now a thumbnail is available it will also show it on the iOS device

##Dependencies

None

##Setup/Usage Instructions

* Get your consumer key and secret key from http://developer.autodesk.com
* You need to set the API keys in the _UserSettings.h file!
* You also need to create a new DropBox app as outlined in the below links and then set the 
"Project TARGETS >> Info >> URL Types >> URL Schemes" based on the app's key  

In order to get a file that can be uploaded it uses the DropBox API to get access to the user's DropBox files. To understand how you can enable an application to use the DropBox API, have a look at these articles:
 - http://www.mathiastauber.com/integration-o-dropbox-in-your-ios-application/
 - https://www.dropbox.com/developers/dropins/chooser/ios

##Written by 

Adam Nagy





    
