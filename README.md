# SMS-Retriever-API

This SMS Retriever API App is an example of the implemetation of the Google's SMS Retriever API.
The reason behind the use of this API is the fact that Google change some critical changes in policy. 
From Jan 19th, 2019 google removed all app from play store with permission CALL_LOG and READ_SMS

# The old way.
1. User had to login in android app on Android Platform.
2. They enter mobile number to receive OTP
3. They gives READ_SMS permission to app for reading SMS.

Recently Google had made some important change in its policy. 
Now Android Platform removes this permission due to data security reasons. 
So now you have to copy code received through SMS. 
Go back to the app and enter that code manually to log in.  

# New way
For overcoming this process, Google introduced SMS Retriever API to automatically fetch a verification code
sent via SMS within the app. This way, user was not required to manually enter the code every time.
