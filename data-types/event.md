---
description: Learn how to use event objects in BuckShotPlusPlus!
---

# Event

Events in [BuckshotPlusPlus ](https://bpplang.com/)play a crucial role in making your application interactive. They allow you to define specific actions or changes that should occur in response to user interactions, such as clicks, mouseovers, or key presses.

## How it works

### Declaring events

Events in [BuckshotPlusPlus ](https://bpplang.com/)are special [views ](view.md)that override or modify other views when they are triggered. You can declare an event using the `event` keyword, followed by the event's name and its properties enclosed in curly braces.

Here's a basic example:

```
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

In this example, an event named `changeTitle` is declared. When the `MyCoolButton` [view ](view.md)is clicked (`onclick`), the `changeTitle` event is triggered, changing the button's content and color.

### Event triggers

Events are triggered by specific user interactions. In the example above, the `onclick` property of the `MyCoolButton` view is set to the `changeTitle` event, meaning the event will be triggered when the button is clicked.

All the [javascript events](https://eqsash.com/articles/vse-obrabotchiki-sobytiy-javascript-polnyy-spisok-s-opisaniem?l=en) can be used as an event trigger in [BuckShotPlusPlus](https://bpplang.com/).

## Use cases

1. **User Interactivity**: Events allow you to create dynamic and interactive applications by responding to user actions.
2. **State Changes**: Use events to change the state or appearance of [views ](view.md)based on specific [conditions ](../the-basics/conditions.md)or interactions.
3. **Feedback**: Provide feedback to users by changing content, colors, or other properties in response to their actions.

## Important notes

* Always give descriptive names to your events to make your code more readable and maintainable.
* Test your events thoroughly to ensure they trigger correctly and produce the desired outcomes.
* Remember that events can override multiple properties of a [view](view.md), so be careful when defining them to avoid unintended changes.
