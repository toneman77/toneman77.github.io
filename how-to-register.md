# how to register
Add zbot as a friend on LINE, PM zbot and say:
>register **user_id** **api_key**

(keep reading)
## what is "user_id"?
User ID is your in-game player ID. You can see it when you log into AT and click on your profile.

## What is api_key?

Every AT account is given a token (api key). This token acts like a signature when speaking to AT servers. If your user id and api key show up at AT servers, AT knows it's you and can answer requests.

## How do I get this stuff?
### zbot method
You can access the information directly through the bot provided you signed up through kongregate. It will not work if you login through facebook. Simply type: 
>konglogin **yourusername yourpassword** 

to zbot. Zbot will spit out two values. The first is the user id; the second is the API key.

### with a browser
You can access the value through a web browser:

1. Open chrome. Ctrl+shift+I will open the network monitor. (Ctrl+shift+e for Firefox)
2. Open AT in the browser.
3. Look for a filter, type "**init**" no quotes.
4. Click on the response that shows up. Look for an entry that says **password=**

-> Your key is 32 characters in length
[back](index)
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE3MDY0MTcxNjYsNzMwOTk4MTE2XX0=
-->