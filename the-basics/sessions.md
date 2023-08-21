---
description: Discover what are sessions and how they work
---

# Sessions

Sessions on bpp enables you to keep track of what a user is doing, the session data object, is a data object accessible inside pages or views and have the following variables in it:

* ip : The current IP address used by the session
* id : The unique ID of the current session
* lang : The user language
* platform: The user platform
* start: A unix timestamp, in milliseconds of the moment the session was created

So for example if you would like to create a text displaying the user ip address you could do:

```
view MyIPTest{
    type = "p"
    content = session.ip
}
```
