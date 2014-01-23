App42_JAVASCRIPT_SDK
====================

App42 Cloud API Client SDK files for JavaScript

1. [Register] (https://apphq.shephertz.com/register) with App42 platform.
2. Create an app once you are on Quick start page after registration.
3. If you are already registered, login to [AppHQ] (http://apphq.shephertz.com/register/app42Login) console and create an app from App Manager Tab.

__Download And Set Up SDK :-__


1. [Download](https://github.com/shephertz/App42_JAVASCRIPT_SDK/archive/master.zip) the App42 Java Script SDK
2. Unzip the file , unzip file will contain version folder , sample folder and plugin for android phoneGap push notication.
3. Version folder will contain App42-all-x.x.x.min.js.
4. Add the following script tag in the your html page

```
<script type="text/javascript" src="App42-all-x.x.x.min.js"/>
```
- Initialize the library using
 
```javascript
App42.initialize("API KEY","SECRET KEY");
```

- Instantiate the service that one wants to use in the App, e.g. using User service one has to do the following

```javascript
var user = new App42User();
```

- Now one can call associated method of that service e.g. user creation can be done with the following snippet

```javascript
user.createUser(userName, pwd, email,{
success: function(object) {
// Callback for Success },
error: function(error) {
    // Callback for error }
});
```

- Executing above method will create user for your app in App42 cloud.
- You can login to AppHQ console and can see the created user there.
- You can also use your UserSample.HTML/StorageSample.HTML shipped with distribution for more details.
- Similarly one can use other App42 services like File Upload, Gaming, NoSQL Storage to make user engaging social Apps for HTML5.


Third Party binaries and respective licenses used in App42 SDK are listed below

Dr Alexander J Turner
----------------------


[CopyRight] (http://nerds-central.blogspot.com/2007/01/fast-scalable-javascript-and-vbscript.html) Dr Alexander J Turner - all rights reserved.

- Please feel free to use this any way you want as long as you
mention I wrote it!

Brian Turek
------------

A JavaScript implementation of the SHA family of hashes, as defined in FIPS
PUB 180-2 as well as the corresponding HMAC implementation as defined in
FIPS PUB 198a.

- Version 1.3 Copyright Brian Turek 2008-2010
- Distributed under the BSD License
- [See] (http://jssha.sourceforge.net/) for more information
- Several functions taken from Paul Johnson
