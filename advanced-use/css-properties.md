---
description: Learn how to use CSS properties in BuckShotPlusPlus
---

# CSS Properties

BuckShotPlusPlus provides comprehensive support for CSS properties, allowing you to style your views and pages with standard CSS properties. The system handles the conversion between BuckShotPlusPlus property names and their DOM equivalents automatically.

### How it works

CSS properties in BuckShotPlusPlus can be applied directly to views using standard property assignment syntax. The system supports all common CSS properties while maintaining a clean and consistent coding style.

#### Declaring CSS Properties

To apply CSS properties to a view, simply declare them as properties within your view definition. Properties use the standard CSS naming convention, with kebab-case names (using hyphens).

Here's a basic example:

```bpp
view MyStyledView {
    background-color = "blue"
    margin-top = "20px"
    font-size = "16px"
    border-radius = "5px"
}
```

#### Supported Properties

BuckShotPlusPlus supports a wide range of CSS properties, including but not limited to:

**Layout Properties**

* align-content
* align-items
* align-self
* display
* flex
* flex-basis
* flex-direction
* flex-flow
* flex-grow
* flex-shrink
* flex-wrap
* grid properties
* justify-content
* position

**Spacing and Sizing**

* margin (and all variants like margin-top, margin-bottom, etc.)
* padding (and all variants)
* width
* height
* max-width
* max-height
* min-width
* min-height

**Visual Styling**

* background (and all variants)
* border (and all variants)
* border-radius
* box-shadow
* color
* opacity

**Typography**

* font-family
* font-size
* font-weight
* letter-spacing
* line-height
* text-align
* text-decoration
* text-transform

**Animation and Transform**

* animation properties
* transform
* transition properties

#### Property Conversion

BuckShotPlusPlus automatically handles the conversion between property names in your code and their DOM equivalents. For example:

```bpp
view MyComponent {
    border-bottom-left-radius = "10px"
}
```

This will be correctly converted to the appropriate CSS property when rendered in the browser.

### Use cases

1.  **Component Styling**: Apply consistent styling to your components using standard CSS properties.

    ```bpp
    view Button {
        background-color = "#007bff"
        padding = "10px 20px"
        border-radius = "5px"
        color = "white"
        cursor = "pointer"
    }
    ```
2.  **Responsive Design**: Create responsive layouts using flexbox and grid properties.

    ```bpp
    view ResponsiveContainer {
        display = "flex"
        flex-wrap = "wrap"
        justify-content = "space-between"
    }
    ```
3.  **Animation and Transitions**: Add dynamic behavior to your components.

    ```bpp
    view AnimatedElement {
        transition = "all 0.3s ease"
        transform = "scale(1)"
        onclick = ScaleUpEvent
    }
    ```

### Important notes

* CSS property names in BuckShotPlusPlus use kebab-case format (with hyphens), matching standard CSS conventions.
* Values for CSS properties should be provided as strings, including numeric values with units.
* The system supports shorthand properties (like `margin: "10px 20px"`) as well as individual properties (like `margin-top: "10px"`).
* When using properties that require vendor prefixes in CSS, BuckShotPlusPlus handles the prefixing automatically.
* Some properties that might affect the content management system's functionality (like 'content') may be restricted for security reasons.

### Best Practices

1. Use consistent units throughout your application (stick to either px, rem, or em).
2. Organize properties in logical groups within your views for better maintainability.
3. Consider creating reusable views with common styling patterns to maintain consistency.
4. Test your styles across different browsers to ensure compatibility.
5. Use meaningful names for views that reflect their styling purpose when appropriate.
