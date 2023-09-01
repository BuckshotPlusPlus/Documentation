---
description: Learn how to use meta tags in BuckShotPlusPlus
---

# Meta tags

You want to add custom meta tags to enhance your website SEO? It's really simple to do in BuckShotPlusPlus!

All you have to do is create a "meta" object. Inside of your meta object, set all your meta properties, like name and content and add your meta object to your page, here is an example:

```
meta Description{
    name = "description"
    content = "A cool description of my website!"
}

page index{
    body = PageTitle
    meta = [Description]
}
```
