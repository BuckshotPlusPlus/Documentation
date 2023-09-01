---
description: Learn how includes works in BuckShotPlusPlus
---

# Include

In [BuckshotPlusPlus](https://bpplang.com/), the `include` directive allows you to incorporate external [BuckshotPlusPlus ](https://bpplang.com/)(bpp) files into your main project. This is particularly useful for modularizing your code, reusing components, or importing libraries and frameworks.

### Local includes

If you have separate bpp files within your project directory or on your local machine, you can include them using the `include` directive followed by the relative path to the file. This allows you to split your code into multiple files for better organization and maintainability.

Here's how you can include a local bpp file:

```
include "local/path/to/your/file.bpp"
```

### Network includes

[BuckshotPlusPlus ](https://bpplang.com/)also supports including bpp files hosted online. This is especially useful when you want to use a library or framework that's hosted on a server or when collaborating with others. To include a network-based bpp file, use the `include` directive followed by the full HTTPS URL of the file.

Here's an example:

```
include "https://link_to_your_bpp_file"
```

## Use cases

1. **Code Modularization**: By splitting your code into multiple files and using the `include` directive, you can create a more organized and modular codebase.
2. **Library and Framework Integration**: Easily integrate external libraries or frameworks hosted online into your [BuckshotPlusPlus ](https://bpplang.com/)project.
3. **Collaboration**: If you're working with a team, you can host shared components online and include them in multiple projects.

## Important notes

* Always ensure that the path or URL you provide in the `include` directive is correct to avoid errors.
* Be cautious when including external files, especially from untrusted sources, to ensure the security and integrity of your project.
* Regularly update the included files, especially if they are libraries or frameworks, to benefit from bug fixes and new features.
