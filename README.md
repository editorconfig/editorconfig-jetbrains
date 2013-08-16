# EditorConfig JetBrains Plugin

A JetBrains IDE plugin supporting the [EditorConfig][] standard.

Supported JetBrains IDEs: IntelliJ IDEA, PyCharm, WebStorm, RubyMine, and more.

## Installation

### Plugin Repository

It is available in the
[JetBrains Plugin Repository](http://plugins.jetbrains.com/plugin/7294), which
can be accessed from within JetBrains IDEs by going to
`Settings > Plugins > Browse repositories...`

### Manual Installation

1. Download plugin release from the [Releases page][].
2. Open settings/preferences
3. Select "Plugins"
4. Click "Install from disk..."
5. Select the .zip (the binary release, not the source, and do not unzip)
6. Follow prompt to restart the IDE

## Supported properties

The EditorConfig JetBrains plugin supports the following EditorConfig
[properties][]:

* indent_style
* indent_size
* tab_width
* end_of_line
* charset
* trim_trailing_whitespace
* insert_final_newline
* root (only used by EditorConfig core)

## Bugs and Feature Requests

Feel free to submit bugs, feature requests, and other issues to the main
[EditorConfig issue tracker][].

[EditorConfig]: http://editorconfig.org
[properties]: http://github.com/editorconfig/editorconfig/wiki/EditorConfig-Properties
[EditorConfig issue tracker]: https://github.com/editorconfig/editorconfig/issues
[Releases page]: https://github.com/editorconfig/editorconfig-jetbrains/releases
