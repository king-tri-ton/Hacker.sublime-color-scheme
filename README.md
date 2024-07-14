```
# Hacker Color Scheme for Sublime Text

A dark, neon-themed color scheme for Sublime Text that gives your coding environment a "hacker" vibe. This color scheme features bright, vibrant colors on a dark background, designed to enhance your coding experience and make your code pop.

![Hacker Color Scheme Screenshot](path/to/screenshot.png)

## Installation

### Package Control

1. Open Sublime Text.
2. Press `Ctrl+Shift+P` (Windows/Linux) or `Cmd+Shift+P` (Mac) to open the Command Palette.
3. Type `Package Control: Install Package` and press `Enter`.
4. Search for `Hacker Color Scheme` and press `Enter` to install.

### Manual Installation

1. Download the `Hacker.sublime-color-scheme` file.
2. Go to the Sublime Text `Packages` directory:
    - Windows: `%APPDATA%\Sublime Text\Packages\User`
    - Mac: `~/Library/Application Support/Sublime Text/Packages/User`
    - Linux: `~/.config/sublime-text/Packages/User`
3. Place the `Hacker.sublime-color-scheme` file in the `User` directory.

## Usage

1. Open Sublime Text.
2. Go to `Preferences` > `Color Scheme`.
3. Select `Hacker Color Scheme`.

## Customization

You can further customize the color scheme by editing the `Hacker.sublime-color-scheme` file. Here are the default settings:

```json
{
    "name": "Hacker Color Scheme",
    "variables":
    {
        "background": "#0d0d0d",
        "foreground": "#00ff00",
        "caret": "#00ff00",
        "comment": "#757575",
        "string": "#00ff00",
        "keyword": "#ff007f",
        "function": "#1e90ff",
        "number": "#ff4500",
        "variable": "#ffd700",
        "type": "#7fff00"
    },
    "globals":
    {
        "background": "var(background)",
        "foreground": "var(foreground)",
        "caret": "var(caret)",
        "line_highlight": "color(var(foreground) alpha(0.1))",
        "selection": "color(var(foreground) alpha(0.2))",
        "selection_border": "color(var(foreground) alpha(0.5))",
        "invisibles": "color(var(foreground) alpha(0.3))",
        "guide": "color(var(foreground) alpha(0.15))",
        "active_guide": "color(var(foreground) alpha(0.35))",
        "stack_guide": "color(var(foreground) alpha(0.25))",
        "highlight": "color(var(foreground) alpha(0.1))"
    },
    "rules": [
        {
            "name": "Comment",
            "scope": "comment",
            "foreground": "var(comment)",
            "font_style": "italic"
        },
        {
            "name": "String",
            "scope": "string",
            "foreground": "var(string)"
        },
        {
            "name": "Keyword",
            "scope": "keyword",
            "foreground": "var(keyword)",
            "font_style": "bold"
        },
        {
            "name": "Function",
            "scope": "entity.name.function",
            "foreground": "var(function)"
        },
        {
            "name": "Number",
            "scope": "constant.numeric",
            "foreground": "var(number)",
            "font_style": "italic"
        },
        {
            "name": "Variable",
            "scope": "variable",
            "foreground": "var(variable)"
        },
        {
            "name": "Type",
            "scope": "storage.type",
            "foreground": "var(type)",
            "font_style": "bold"
        }
    ]
}
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Enjoy your new hacker-themed coding environment! If you have any issues or suggestions, feel free to open an issue on GitHub.

```
