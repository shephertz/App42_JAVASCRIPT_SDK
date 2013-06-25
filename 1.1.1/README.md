App42_JAVASCRIPT_SDK
====================

App42 Cloud API Client SDK JAR files for JavaScript

- [Download] (https://github.com/shephertz/App42_JAVASCRIPT_SDK/raw/master/1.1/app42_javaScript_1.1.zip) the latest App42 Java Script SDK
- Unzip the file and copy App42-all-x.x.x.min.js to your project  source.
- Add the following script tag in the your html page
script type="text/javascript" src="App42-all-x.x.x.min.js"
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
