---
description: Discover what is the data datatype and how to use it
---

# Data

In [BuckshotPlusPlus](https://bpplang.com/), the `data` datatype represents a structured set of information that cannot be directly rendered as visual content. While it shares similarities with the [view ](view.md)datatype, its primary purpose is to hold and manage data rather than define visual elements.

## How it works

### Declaring data

Data objects in [BuckshotPlusPlus ](https://bpplang.com/)are declared similarly to [views](view.md). However, unlike [views](view.md), they don't have properties related to visual rendering. Instead, they contain properties that define specific pieces of data or information.

For instance, the [session ](../the-basics/sessions.md)object in [BuckshotPlusPlus ](https://bpplang.com/)is of type `data`. This object contain properties related to a user's session, such as session ID, user preferences, or authentication tokens (coming soon).

### Using data

While data objects can't be rendered directly, they can be referenced and used within [views ](view.md)or other parts of your application. For example, you might use a data object to store configuration settings and then reference those settings within a [view ](view.md)to determine its behavior or appearance.

## Use cases

1. **Storing Configuration**: Data objects can be used to store configuration settings or other non-visual data that your application needs to reference.
2. **Data Relationships**: Data objects can reference other data objects or [views](view.md), allowing you to establish relationships between different pieces of data.

## Important notes

* Always ensure that data objects are used for their intended purpose: to store and manage data. Avoid trying to use them as substitutes for views or other visual elements.
* Organize and structure your data objects in a way that makes them easy to manage and reference throughout your application.
