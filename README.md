# Sublime Text - eazyBI MDX Syntax Highlighting

This repository contains a Sublime Text syntax highlighting file specifically for the eazyBI variant of the [Multidimensional Expressions (MDX) query language](https://mondrian.pentaho.com/documentation/mdx.php). This is not to be confused with [MDX (Markdown + JSX)](https://mdxjs.com/), a completely different language used for seamlessly writing JSX in Markdown documents.

MDX is a language for defining and manipulating multidimensional data widely used in Business Intelligence tools. It allows querying and manipulating multidimensional data cubes in a more human-readable format. eazyBI has specific additional MDX functions that are unavailable in the standard Mondrian OLAP engine, and some general MDX functions may be missing.

This syntax highlighting is specifically tailored to the MDX functions available in [eazyBI](https://docs.eazybi.com/eazybi/analyze-and-visualize/calculated-measures-and-members/mdx-function-reference).

![Example](./example.png)

## Installation

### Package Control (Recommended)
Package Control is a package manager for Sublime Text. If you don't already have it installed, follow the [installation instructions here](https://sublime.wbond.net/installation).

Once Package Control is installed, restart Sublime and follow these steps:

1. Open the Command Pallette (`cmd + shift + p` on OS X / Linux or `ctrl + shift + p` on Windows).
2. Type "install" and select `Package Control: Install Package`.
3. Type "eazyBI MDX" and press Enter.
4. Restart Sublime Text. 

After following these steps, Sublime Text should automatically use eazyBI MDX syntax highlighting for files with the `.mdx` extension.

### Manually
1. Download the `MDX.sublime-syntax` file from this repository.
2. Open Sublime Text and click on `Preferences > Browse Packages`. This will open the Sublime Text packages directory.
3. Copy the downloaded `MDX.sublime-syntax` file into the appropriate directory:

    - On MacOS: `/Users/{username}/Library/Application Support/Sublime Text 3/Packages/User/`
    - On Windows: `C:\Users\{username}\AppData\Roaming\Sublime Text 3\Packages\User\`
    - On Linux: `~/.config/sublime-text-3/Packages/User/`
   
   Be sure to replace `{username}` with your actual username on your system.

4. Restart Sublime Text.

After following these steps, Sublime Text should automatically use eazyBI MDX syntax highlighting for files with the `.mdx` extension.

## Contributing

Contributions to improve this syntax highlighting template are very welcome. Feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
