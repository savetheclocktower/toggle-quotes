# Toggle Quotes

[![Build Status](https://travis-ci.org/atom/toggle-quotes.svg?branch=master)](https://travis-ci.org/atom/toggle-quotes)
[![Dependency Status](https://david-dm.org/atom/toggle-quotes.svg)](https://david-dm.org/atom/toggle-quotes)

Toggle a single-quoted string to a double-quoted string, and vice versa.

![toggle-quotes-demo](https://f.cloud.github.com/assets/2988/1764634/c1098d1e-6729-11e3-88f4-73cc336c0173.gif)

This is a package for [Atom](https://atom.io), a hackable text editor for the 21st Century.

## Usage

Search for `Toggle Quotes: Toggle` in the Command Palette or enter the keybinding for your system to toggle quotes on a string. Only available when using any grammar that supports single-quoted and double-quoted strings, or any other configured string character (e.g. JavaScript, Python, Ruby, etc.).

### Commands
Command                | Description
-----------------------|--------------
`toggle-quotes:toggle` | Toggles the quote characters used for quoted strings between the configured `Quote Characters` (`'` and `"` by default).

### Keybindings

Command            | Linux  | OS X  | Windows
-------------------|--------|-------|----------
`toggle-quotes:toggle` | <kbd>Ctrl-"</kbd> | <kbd>Cmd-"</kbd> | <kbd>Ctrl-"</kbd>

Custom keybindings can be added by referencing the above commands.  To learn more, visit the [Using Atom: Basic Customization](https://atom.io/docs/latest/using-atom-basic-customization#customizing-key-bindings) or [Behind Atom: Keymaps In-Depth](https://atom.io/docs/latest/behind-atom-keymaps-in-depth) sections in the flight manual.

### Configuration

Configuration Key Path      | Type | Default | Description
----------------------------|------|---------|------------
`toggle-quotes.quoteCharacters` | `string` | `'"` | The characters `toggle-quotes:toggle` toggles between. No whitespace.

## License

[MIT License](http://opensource.org/licenses/MIT) - see the [LICENSE](https://github.com/atom/toggle-quotes/blob/master/LICENSE.md) for more details.
