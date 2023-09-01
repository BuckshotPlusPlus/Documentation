---
description: Discover how to use page objects in BuckShotPlusPlus!
---

# Page

In [BuckshotPlusPlus](https://bpplang.com/), pages represent the individual screens or web pages of your application. While they are similar to [views](view.md), pages are specifically designed to define the structure and content of a complete web page.

## How it works

### Declaring pages

To declare a page in [BuckshotPlusPlus](https://bpplang.com/), you use the `page` keyword followed by the name of the page and its properties enclosed in curly braces. The properties of a page define its title, body and other attributes.

Here's a basic example:

```
page index{
	title = "My Index!"
	body = My_Body_View
}
```

In this example, a page named `index` is declared with a title "My Index!" and a body content defined by the `My_Body_View` view.

### Page URLs

The name of the page determines its URL. For instance, the `index` page corresponds to the root URL (`/`). If you name your page something other than `index`, the page's URL will be based on its name. For example:

```
page blog{
	title = "My cool blog!"
	body = My_Blog_Body_View
}
```

This will create a page accessible at the `/blog` URL.

## Use cases

1. **Website Structure**: Pages allow you to define the structure of your website, specifying which content appears on which page.
2. **Dynamic Content**: By associating different views with different pages, you can create dynamic web pages that change based on user interactions or other conditions.
3. **SEO Optimization**: By giving descriptive names and titles to your pages, you can improve the search engine optimization ([SEO](https://en.wikipedia.org/wiki/Search\_engine\_optimization)) of your website.

## Important notes

* Always use descriptive names for your pages to make your website more user-friendly and improve [SEO](https://en.wikipedia.org/wiki/Search\_engine\_optimization).
* Ensure that the [views ](view.md)associated with a page are correctly defined and tested to avoid rendering issues.
* Remember that the name of the page determines its URL, so choose names that are relevant to the content of the page.
