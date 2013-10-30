App42_BPaaS_JavaScript_SDK
====================

App42 BPaaS Cloud API Client SDK for JavaScript

- Download the App42 BPaaS Java Script SDK
- Unzip the file and copy App42-BPaaS-all-x.x.x.min to your project  source.
- Add the following script tag in the your html page

```
<script type="text/javascript" src="../App42-BPaaS-all-x.x.x.min.js">
```

- Initialize the library using :-

```
App42.initialize("<YOUR_API_KEY>","<YOUR_SECRET_KEY>");
App42.setBaseUrl("<YOUR_BPAAS_API_SERVER_URL>");
```

- Instantiate the service that one wants to use in the App, e.g. using User service one has to do the following

```
var userService = new App42User();
```

- Now one can call associated method of that service e.g. user creation can be done with the following snippet

```
var userName = "<Enter your username>",
password = "<Enter your password>",
emailId = "<Enter your emailId>";
user.createUser(userName, password, emailId,
{
	success: function(object) {
	 // Callback for Success 
	},
    error: function(error) {
   // Callback for error 
	}
});
```

- Executing above method will create user for your app in App42 BPaaS cloud.
- You can login to BPaaS AppHQ console and can see the created user there.
- You can also use your UserSample.HTML/StorageSample.HTML shipped with distribution for more details.
- Similarly one can use other App42 BPaaS services like File Upload, Gaming, NoSQL Storage to make user engaging social Apps for HTML5.


Third Party binaries and respective licenses used in App42 BPaaS SDK are listed below

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
