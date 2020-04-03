# registered commands

xox

## zbot admin

these are commands mainly used by the person that _manages_ zbot for the whole guild

### room stuff

| command 				| what it does |
| -- | -- |
| list rooms 			| list all zbot rooms that are connected to the LINE account 	|
| add room _roomname_ 	| adds this room to the admin's list of rooms  					|
| rem room _id_ 		| remove the room with the id _id_ from the list of rooms 		|

### user stuff

| command | what it does |
| -- | -- |
| add user _add code_ _level_ _ingamename_ | add a user. That user has to generate a code with the [add me TODO](TODO) command before. [example](#exadduser). [about levels TODO](TODO) |
| list users 		| lists all users that were added to the room via the **add user** command |
| rem user _id_ 	| removes the user with the id _id_ (see above: **list user**) and revokes the access rights |

## utility stuff

| command | what it does |
| -- | -- |
| update guild | updates your guild info and access after **changing guilds** |
| lock | zbot takes every precaution to ensure you (zbot admin) are not in a battle. However, if you want peace of mind use **lock** |
| unlock | once you used the **lock** command all zbot commands that user practice battles (see [here TODO](TODO)) are blocked. This commands unlocks all those commands again |

## registered deck commands

this is the stuff beyond the usual fmapping. None of these commands need you to change the deck in-game. Since you are registered you just use the correct deck number _#_

**If** the deck number is omitted your currently active deck will be used.

| command | what it does |
|--|--|
| **d** | shows a list of decks and the name you chose for that deck |
| mf _#_ | **fmap** for deck number _#_, [see](deck-building) |
| md _#_ | **deck** for deck number _#_, [see](deck-building) |
| mc _#_ | **cmap** for deck number _#_, [see](deck-building) |
| ma _#_ | **analyze** for deck number _#_, [see](deck-building) |
| ms _#_ | **stat** for deck number _#_, [see](deck-building) |
| map _#_ | analyze with fmap for deck number _#_, [see](deck-building) |
| mch _#_ | **char** for deck number _#_, [see](deck-building) |
| mfr _#_ | **fmap** and **missing research** for deck number _#_ |
| smap _#_ | **fmap** plus swole bonus for deck number _#_ |

## inventory commands

The commands that unlock the full potential

| command | what it does |
|--|--|
| mi _filter_ | **m**y **i**nventory. shows the inventory filtere by [a filter TODO](#filter). [example TODO](TODO) |
| research _show_/_trait_/_legchar_ | shows missing research filtered by show and/or trait and/or leg(for legendaries) or char(acter cards) |
| mif _show/trait_ | **m**y **i**nventory **f**map. fmap of your inventory filtered by show and/or trait [example](TODO) |
| mcm | **m**y **c**ombo **m**astery: shows all bought combo masteries |

### filters

available filters:
> char leg item pc trait show skill

## examples

TODO

> [back](index)
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTg4NjE4OTk2MywxNDUwMDM4MTUsMTcwNj
U0MzkzNywtMjAwMjM0NDM2Niw4OTIxNjM4NDZdfQ==
-->