---
description: Learn how to use meta tags in BuckShotPlusPlus
---

# Meta tags

Meta tags play a pivotal role in enhancing the visibility and [SEO ](https://en.wikipedia.org/wiki/Search\_engine\_optimization)(Search Engine Optimization) of your website. In [BuckshotPlusPlus](https://bpplang.com/), adding custom meta tags is straightforward, allowing you to provide essential metadata about your web pages to search engines and other web services.

## How it works

### Declaring meta tags

In [BuckshotPlusPlus](https://bpplang.com/), you can declare meta tags using the `meta` keyword. Each meta tag is defined as an object with properties that specify the meta tag's name and content.

Here's a basic example:

```
meta Description{
    name = "description"
    content = "A cool description of my website!"
}
```

In this example, a meta tag named `Description` is declared with a `name` property set to "description" and a `content` property set to "A cool description of my website!".

### Associating meta tags with pages

Once you've defined your meta tags, you can associate them with specific pages using the `meta` property of the [page ](../data-types/page.md)object. This ensures that the meta tags are included in the HTML head section of the corresponding web page.

Here's how you can associate the `Description` meta tag with an `index` [page](../data-types/page.md):

```
page index{
    body = PageTitle
    meta = [Description]
}
```

## Use cases

1. **SEO Optimization**: Improve the search engine ranking and visibility of your web pages by providing relevant meta information.
2. **Social Media Sharing**: Use meta tags to define how your web pages appear when shared on social media platforms like Facebook or Twitter.
3. **Browser Behavior**: Control browser behavior, such as setting the viewport or specifying the character set, using specific meta tags.

## Important notes

* Ensure that your meta tags provide accurate and relevant information about your web pages.
* Regularly update your meta tags to reflect any changes or updates to your web content.
* Test your web pages using SEO tools to ensure that the meta tags are correctly recognized and processed by search engines.
