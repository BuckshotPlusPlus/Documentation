---
description: Learn how to use event objects in BuckShotPlusPlus!
---

# Event

Events in BuskShot++ are view that will override an other view, when they are called.

Here is an example on how to create an event, that will change the content and color of my view on click:

````
```bpp
event changeTitle{
    content = "You already clicked!"
    color = "red"
}

view MyCoolButton{
    type = "button"
    content = "Click on me!"
    onclick = changeTitle
    cursor = "pointer"
}

```
````

If you try this on your bpp project, you will see the content of the button change to "You already clicked!" in red once you click the button!
