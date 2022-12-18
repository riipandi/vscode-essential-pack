# Essential Extension Pack for Visual Studio Code

Collection of basic extensions to get started with web development in Visual Studio Code.
The goal is provide extensions for web developer that available in VSCode Web and Gitpod
to extend VSCode functionality.

## Sample Configuration

```json
{
  "window.autoDetectColorScheme": false,
  "workbench.colorTheme": "Gitpod Dark",
  "workbench.preferredDarkColorTheme": "Gitpod Dark",
  "workbench.preferredLightColorTheme": "Gitpod Light",
  "workbench.productIconTheme": "icons-carbon",
  "workbench.iconTheme": "dot_small_gray",
  "workbench.tree.indent": 14,
  "workbench.reduceMotion": "on",
  "workbench.editor.enablePreview": true,
  "editor.wordWrap": "off",
  "html.autoClosingTags": true,
  "html.format.endWithNewline": true,
  "html.format.indentHandlebars": true,
  "emmet.triggerExpansionOnTab": true,
  "auto-close-tag.enableAutoCloseTag": true,
  "auto-close-tag.enableAutoCloseSelfClosingTag": true,
  "auto-rename-tag.activationOnLanguage": [
    "html",
    "xml",
    "php",
    "javascript",
    "vue"
  ],
  "[markdown]": {
    "editor.quickSuggestions": false
  }
}
```

## Building Extension

You need a Personal Access Token. Read the [documentation here](https://code.visualstudio.com/api/working-with-extensions/publishing-extension#get-a-personal-access-token).

```sh
npm i -g vsce
```

```sh
vsce package
vsce login PUBLISHER_ID
vsce publish
```

## Contact

Please file any [issues](https://github.com/riipandi/vscode-essential-pack/issues) or
have a suggestion please tweet me [@riipandi](https://twitter.com/riipandi).

## License

This project is open-sourced software licensed under the [MIT license](./LICENSE).
