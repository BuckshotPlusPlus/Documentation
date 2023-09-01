---
description: Learn how to use arrays in BuckShotPlusPlus
---

# Arrays

Arrays in [BuckshotPlusPlus ](https://bpplang.com/)are data structures that allow you to store multiple values in a single [variable](variables.md). They are particularly useful when you want to group related data together or when you need to manage a collection of items, such as [views](view.md).

## How it works

### Declaring arrays

In [BuckshotPlusPlus](https://bpplang.com/), arrays are declared using square brackets `[]`. Each item in the array is separated by a comma. Arrays can be used in various places within your code, such as assigning multiple [views ](view.md)to the content of another [view](view.md).

Here's a basic example:

```
view MyView{
    content = [Child1, Child2]
}
```

In this example, the `content` property of the `MyView` [view ](view.md)is assigned an array containing two [views](view.md): `Child1` and `Child2`.

## Use cases

1. **Grouping Related Data**: Arrays allow you to group related data together, making your code more organized and easier to manage.

## Important notes

* Always ensure that the items you place in an array are of a consistent type or are expected by the property or function you're assigning the array to.
* Be mindful of the order of items in an array, as this can affect how they are displayed or processed.
* While arrays are powerful, ensure you use them appropriately and avoid unnecessary complexity in your code.
