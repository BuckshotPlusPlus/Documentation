---
description: Discover how to use page objects in BuckShotPlusPlus!
---

# Page

A page object is similar to a [view](view.md) object, but is used to create new pages, here is how you create a new page in bpp:

```
page index{
	title = "My Index!"
	body = My_Body_View
}
```

This will create an index page, the index page is a special keyword and will be accessible trough the / url, but if you set something else as the page name, like blog, then your page would be accessible trough /blog, here is an example:

```
page blog{
	title = "My cool blog!"
	body = My_Blog_Body_View
}
```
