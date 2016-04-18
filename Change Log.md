* [Release Version 3.0](https://github.com/shephertz/App42_JAVASCRIPT_SDK/blob/master/Change%20Log.md#version-30)
* [Release Version 2.9.1](https://github.com/shephertz/App42_JAVASCRIPT_SDK/blob/master/Change%20Log.md#version-291)
* [Release Version 2.9](https://github.com/shephertz/App42_JAVASCRIPT_SDK/blob/master/Change%20Log.md#version-29)
* [Release Version 2.8](https://github.com/shephertz/App42_JAVASCRIPT_SDK/blob/master/Change%20Log.md#version-28)
* [Release Version 2.7.2](https://github.com/shephertz/App42_JAVASCRIPT_SDK/blob/master/Change%20Log.md#version-272)
* [Release Version 2.7.1](https://github.com/shephertz/App42_JAVASCRIPT_SDK/blob/master/Change%20Log.md#version-271)
* [Release Version 2.7](https://github.com/shephertz/App42_JAVASCRIPT_SDK/blob/master/Change%20Log.md#version-27)
* [Release Version 2.6](https://github.com/shephertz/App42_JAVASCRIPT_SDK/blob/master/Change%20Log.md#version-26)
* [Release Version 2.5](https://github.com/shephertz/App42_JAVASCRIPT_SDK/blob/master/Change%20Log.md#version-25)
* [Release Version 2.4](https://github.com/shephertz/App42_JAVASCRIPT_SDK/blob/master/Change%20Log.md#version-24)
* [Release Version 2.3](https://github.com/shephertz/App42_JAVASCRIPT_SDK/blob/master/Change%20Log.md#version-23)
* [Release Version 2.2](https://github.com/shephertz/App42_JAVASCRIPT_SDK/blob/master/Change%20Log.md#version-22)
* [Release Version 2.1](https://github.com/shephertz/App42_JAVASCRIPT_SDK/blob/master/Change%20Log.md#version-21)
* [Release Version 2.0](https://github.com/shephertz/App42_JAVASCRIPT_SDK/blob/master/Change%20Log.md#version-20)
* [Release Version 1.9.1](https://github.com/shephertz/App42_JAVASCRIPT_SDK/blob/master/Change%20Log.md#version-191)
* [Release Version 1.9](https://github.com/shephertz/App42_JAVASCRIPT_SDK/blob/master/Change%20Log.md#version-19)
* [Release Version 1.8](https://github.com/shephertz/App42_JAVASCRIPT_SDK/blob/master/Change%20Log.md#version-18)
* [Release Version 1.7](https://github.com/shephertz/App42_JAVASCRIPT_SDK/blob/master/Change%20Log.md#version-17)

## Version 3.0

**Release Date:** 14-07-2015

**Release Version:** 3.0

**Feature :** 

```
In-App Messaging
```

**This release contains the following bug fix:**
```
None.
```

## Version 2.9.1

**Release Date:** 27-02-2015

**Release Version:** 2.9.1

**The following Service have been pushed :**

```
NONE
```

**This release contains the following bug fix:**

```
Delete message by id bug fix
```

## Version 2.9

**Release Date:** 17-12-2014

**Release Version:** 2.9

**The following Service have been pushed :**

```
1. Event Service.
2. Queue Service.
```

**This release contains the following bug fix:**

```
None
```

## Version 2.8

**Release Date:** 03-11-2014

**Release Version:** 2.8

**The following Service have been pushed :**

```
BravoBoard Service
```

**This release contains the following bug fix:**

```
None
```

## Version 2.7.2

**Release Date:** 01-09-2014

**Release Version:** 2.7.2


**This release contains the following bug fix:**

```
Bug fix in user service
```

## Version 2.7.1

**Release Date:** 26-08-2014

**Release Version:** 2.7.1


**This release contains the following bug fix:**

```
Bug fix in storage service
```


## Version 2.7

**Release Date:** 20-08-2014

**Release Version:** 2.7

**The following features have been pushed :**
```
New NokiaX enum added in push DeviceType.
```

**The following features have been pushed to the services :**

**PUSH SERVICE**

```
deleteChannel
getChannelUsersCount
getChannelUsers
getUserSubscribedChannelsCount
getUserSubscribedChannels
```

**STORAGE SERVICE**

```
setCreatedOn
setUpdatedOn
setDocumentId
```

**AVATAR SERVICE**

```
updateAvatar
deleteAvatarByName
deleteAllAvatars
```
**This release contains the following bug fix:**

```
None
```

## Version 2.6

**Release Date:** 20-06-2014

**Release Version:** 2.6

**The following Services have been pushed to the latest :**
```
Timer Service
Gift Service
```
**This release contains the following bug fix:**

```
None
```


## Version 2.5

**Release Date:** 20-06-2014

**Release Version:** 2.5

**The following features have been pushed :**
```
New NokiaX enum added in push DeviceType.
```

**The following features have been pushed to the services :**

**PUSH SERVICE**

```
updatePushBadgeforDevice
updatePushBadgeforUser
clearAllBadgeCount
```


**SCORE BOARD SERVICE SERVICE**

```
getUsersWithScoreRange
```
**This release contains the following bug fix:**

```
None
```


## Version 2.4

**Release Date:** 01-04-2014

**Release Version:** 2.4


**The following features have been pushed  :**

```
If you are upgrading from previous version of App42-all-2.3.min and have used setQuery method on any service, you have to set App42.setDbName instead of passing it in method parameter.

**OlD Code Snippet:
setQuery("dbName","collectionName","query");

**New Code Snippet :
App42.setDbName("dbName");
setQuery("collectionName","query");
```

**The following features have been pushed to the services :**

**STORAGE SERVICE**

```
addOrUpdateKeys
addAttachmentToDocs
insertJSONDocumentWithFile
```


**REVIEW SERVICE**

```
getAllReviewsByUser
```


**USER SERVICE**

```
addJSONObject(Add Extra Information while creating user)
```

**SCOREBOARD SERVICE**

```
addJSONObject(Add Extra Information of user while saves score)
```

**This release contains the following bug fix:**

```
None
```


## Version 2.3

**Release Date:** 04-02-2014

**Release Version:** 2.3


**The following features have been pushed to the services :**

**STORAGE SERVICE**

```
updateDocumentByQuery
```

**BUDDY SERVICE**

```
unFriend
deleteMessageById
deleteMessageByIds
```

**PHOTO SERVICE**

```
updatePhoto
```

**This release contains the following bug fix:**

```
None
```


## Version 2.2

**Release Date:** 23-01-2014

**Release Version:** 2.2


**The following features have been pushed  :**

```
Meta info in UserService (getUser,getUsersByRole,getUserByEmailId) and ScoreBoardService(getTopNRankers).
```


**The following features have been pushed to the services :**

**PUSH SERVICE**

```
sendMessageToInActiveUsers
scheduleMessageToUser

```

**REVIEW SERVICE**

```
deleteReviewByReviewId
deleteCommentByCommentId
```

**SCOREBOARD SERVICE**

```
getTopNTargetRankers
getTopNRankersFromFacebook(With specefied dange range)
```

**This release contains the following bug fix:**

```
None
```


## Version 2.1

**Release Date:** 03-12-2013

**Release Version:** 2.1


**The following Service have been pushed to the latest :**

```
Custom Code Service
```

**This release contains the following bug fix:**

```
None
```

## Version 2.0

**Release Date:** 29-11-2013

**Release Version:** 2.0


**The following Service have been pushed to the latest :**

```
Push Notification Service
```

**This release contains the following bug fix:**

```
None
```

## Version 1.9.1

**Release Date:** 25-11-2013

**Release Version:** 1.9.1


**The following features have been pushed :**

```
Set logged in user
```

**The following features have been pushed to the storage service :**

```
saveOrUpdateDocumentByKeyValue
```

**This release contains the following bug fix:**

```
Bux fix of setEvent in LogService
```

## Version 1.9

**Release Date:** 22-10-2013

**Release Version:** 1.9

**The following Service have been pushed to the latest :**

```
AB Test Service
```

**This release contains the following bug fix:**

```
None
```

## Version 1.8

**Release Date:** 23-09-2013

**Release Version:** 1.8

**The following Service have been pushed to the latest :**

```
Avatar Service
Achievement Service
```

**The following features have been pushed to the Social Service :**

```
facebookPublishStream
facebookLinkPost
facebookLinkPostWithCustomThumbnail
getFacebookProfile
```

**This release contains the following bug fix:**

```
None
```


## Version 1.7

**Release Date:** 11-09-2013

**Release Version:** 1.7

**The following Service have been pushed to the latest :**

```
Cart Service
Catalogue Service
ImageProcessor Service
```

**This release contains the following bug fix:**

```
None
```



