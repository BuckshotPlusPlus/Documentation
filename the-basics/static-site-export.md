---
description: Learn how to export static websites in BuckShotPlusPlus
---

# Static site export

[BuckshotPlusPlus ](https://bpplang.com/)offers a powerful feature that allows you to export your dynamic application as a static website. This is especially useful when you want to host your application on platforms that primarily support static content or when you aim to improve performance and reduce server-side processing.

## How it works

### Export command

To export your [BuckshotPlusPlus ](https://bpplang.com/)application as a static website, you use the `export` command provided by the [BuckshotPlusPlus ](https://bpplang.com/)executable. This command takes in the path to your main [BuckshotPlusPlus ](https://bpplang.com/)file (typically `main.bpp`) and the directory where you want the static files to be exported.

Here's the syntax for the export command:

```sh
BuckShotPlusPlus.exe export "path/to/your/main.bpp" "path/to/your/export/folder"
```

Upon executing this command, [BuckshotPlusPlus ](https://bpplang.com/)will process your application, generate the necessary HTML, CSS, and JavaScript files, and save them to the specified export directory.

## Use cases

1. **Hosting on Static Platforms**: Easily deploy your [BuckshotPlusPlus ](https://bpplang.com/)application on platforms like [GitHub Pages](https://pages.github.com/), [Netlify](https://www.netlify.com/), or [Vercel ](https://vercel.com/)that are optimized for static content.
2. **Improved Performance**: Static websites generally load faster and require less server-side processing, offering a better user experience.
3. **Reduced Server Costs**: By serving static files, you can reduce the computational load on your servers, potentially leading to cost savings.

## Important notes

* Ensure that all paths provided to the `export` command are correct to avoid errors during the export process.
* Test the exported static site thoroughly to ensure that all features and functionalities work as expected.
* Remember that while static sites offer many advantages, they might not be suitable for applications that require real-time data or server-side processing.
