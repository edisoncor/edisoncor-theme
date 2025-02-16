# Edisoncor Theme

This sample color theme is for personal use and contains two TextMate themes.

Text Mate themes describe the theming rules used for syntax highlighting. Each rule consists of one or more scope selectors and a set of styles. To learn more about scopes and how they're used, check out the [color theme](https://code.visualstudio.com/api/extension-guides/color-theme) documentation.

You can directly use .tmTheme files in your extensions or import/convert them with VS Code's extension generator [yo code](https://code.visualstudio.com/api/get-started/your-first-extension).

## Theme Descriptions

### Edisoncor Theme

"Edisoncor Theme" is a dark theme designed to provide a comfortable coding experience with soft colors and balanced contrasts. This theme is ideal for working in low-light environments and reduces eye strain during long coding sessions.

### Edisoncor Light Theme

"Edisoncor Light Theme" is a light theme that offers a clean and bright appearance. It is perfect for well-lit environments and provides excellent readability with vivid and well-defined colors.

## Repository

You can find the theme repository on [GitHub](https://github.com/edisoncor/edisoncor-theme).

## Demo

Sample Light

![Sample light](./demo-light.png)

Sample Dark

![Sample dark](./demo-dark.png)

## VS Code API

### Contribution Points

- [contributes.themes](https://code.visualstudio.com/api/references/contribution-points#contributes.themes)

## Running the sample

- Press `F5` to open a new window with your extension loaded.
- Open `File > Preferences > Color Themes` (or `Code > Preferences > Color Theme` on macOS), and pick `Sample Light` or `Sample Dark`.
- Open a file that has a language associated. The languages' configured grammar will tokenize the text and assign 'scopes' to the tokens. To examine these scopes, invoke the `Inspect TM Scopes` command from the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P` on Mac).

## Make changes

- You can relaunch the extension from the debug toolbar after making changes to the files listed above.
- You can also reload (`Ctrl+R` or `Cmd+R` on Mac) the VS Code window with your extension to load your changes.