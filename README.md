# WPCS whitelist flags for Sublime Text

A [Sublime Text  2/3](http://www.sublimetext.com/) plug-in to add [WordPress Coding Standards whitelist flags](https://github.com/WordPress-Coding-Standards/WordPress-Coding-Standards/wiki/Whitelisting-code-which-flags-errors) to your php code.

## Use

Type `wpcs` to select a whitelist flag via autocomplete.

## Install via Package Control

1. [Install Package Control](https://packagecontrol.io/installation) if you haven't yet.
2. Open the command palette (<kbd>Ctrl+Shift+P</kbd> for Windows/Linux, <kbd>Cmd+Shift+P</kbd> for Mac).
3. Search for _Package Control: Install Package_ and hit <kbd>Enter</kbd>.
4. Type `WPCS whitelist flags` and press <kbd>Enter</kbd> to install it.

## Changelog

### 1.0.6
- Add PreparedSQLPlaceholders replacement count flag

### 1.0.5
- Make precision alignment flag available to .js and .css files

### 1.0.4
- Tab triggers now contain more words.
This makes it easier to select a specific flag via the keyboard in addition to using the up or down arrow keys

### 1.0.3
- Add precision alignment flag (props @claudiosanches)

### 1.0.2
- Remove `tax_query` flag

### 1.0.1
- Add new whitelist flags for WPCS 0.12.0+
- Add `tax_query` flag deprecation notice

### 1.0.0
- Initial release
