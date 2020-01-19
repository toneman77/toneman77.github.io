# how to use multiple accounts
The situation might arise where you are in charge of more than one account. For this multiple account support is built into zbot

Prerequisite for **this** doc is that you already have at least one account registered already.

TODO: more text here

## steps

1. create a new group
this new group will now act as your personal PM access for the "additional" account that you want to add
2. say:
   > create new account
  
   This will make zbot behave like this is a brand new LINE account. you can now use the [add me](TODO) command to be added to your guild's zbot room or the [register](TODO) command to register this new account to zbot.

## linking rooms
The situation might arise where you have already 2 or more accounts linked to your LINE account via the method mentioned above. If you now join a LINE room with zbot in it zbot has no way of knowing **which** account of yours you want to use in there so:
* join the room with zbot in it
* say
  > link room

  and zbot will reply with a list like:
  > id | guild
  > 1 | fancy guild
  > 2 | awesome guild
  > 3 | lounging guild
  
 * depending on what accounts infos you wanna use in this room say:
   > link room 2
 
   (2 is just an example, choose accordingly) and from now on zbot will refer to the account that is in the guild you chose. side note: this number may change over time as you add more accounts so be sure to really **read** what the **link room** command replies

> [back](index)
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEwMzA3OTM4NDYsMTQxNzczMTAyMF19
-->