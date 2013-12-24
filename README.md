SublimeLinter-pyyaml
=========================

This linter plugin for [SublimeLinter](https://github.com/SublimeLinter/SublimeLinter3) provides an interface to [pyyaml](http://pyyaml.org/). It will be used with files that have the “YAML” syntax.

## Installation
SublimeLinter 3 must be installed in order to use this plugin. If SublimeLinter 3 is not installed, please follow the instructions [here](https://github.com/SublimeLinter/SublimeLinter.github.io/wiki/Installation).

### Linter installation
Before using this plugin, you must ensure that `pyyaml` is installed on your system, and **available for direct import in Sublime Text 3**. To install `pyyaml`, do the following:

1. Install [Python](http://python.org/download/) and [pip](http://www.pip-installer.org/en/latest/installing.html).

1. Install `pyyaml` by typing the following in a terminal:
   ```
   [sudo] pip-3.X install pyyaml
   ```

Once `pyyaml` is installed, you can proceed to install the SublimeLinter-pyyaml plugin if it is not yet installed.

### Plugin installation
Please use [Package Control](https://sublime.wbond.net/installation) to install the linter plugin. This will ensure that the plugin will be updated when new versions are available. If you want to install from source so you can modify the source code, you probably know what you are doing so we won’t cover that here.

To install via Package Control, do the following:

1. Within Sublime Text, bring up the [Command Palette](http://docs.sublimetext.info/en/sublime-text-3/extensibility/command_palette.html) and type `install`. Among the commands you should see `Package Control: Install Package`. If that command is not highlighted, use the keyboard or mouse to select it. There will be a pause of a few seconds while Package Control fetches the list of available plugins.

1. When the plugin list appears, type `pyyaml`. Among the entries you should see `SublimeLinter-pyyaml`. If that entry is not highlighted, use the keyboard or mouse to select it.

1. When the module is installed and you open a “YAML” file, you should see a message stating ``SublimeLinter: pyyaml activated: <builtin>`` or similar in the console. The message should be similar to ``SublimeLinter: yaml imported <module 'yaml' from '/usr/local/lib/python3.3/dist-packages/yaml/__init__.py'>`` if debug mode is on.

1. If you see ``SublimeLinter: WARNING: import of yaml module in pyyaml failed`` instead, try running ``import yaml`` in the SublimeText console. If it fails, the module could not be located, please see [Troubleshooting](https://github.com/SublimeLinter/SublimeLinter.github.io/wiki/Troubleshooting), or use the [SublimeLinter google group](https://groups.google.com/forum/#!forum/sublimelinter) to report installation and configuration problems.

## Settings
For general information on how SublimeLinter works with settings, please see [Settings](https://github.com/SublimeLinter/SublimeLinter.github.io/wiki/Settings). For information on generic linter settings, please see [Linter Settings](https://github.com/SublimeLinter/SublimeLinter.github.io/wiki/Linter-Settings).

## Contributing
If you would like to contribute enhancements or fixes, please do the following:

1. Fork the plugin repository.
1. Hack on a separate topic branch created from the latest `master`.
1. Commit and push the topic branch.
1. Make a pull request.
1. Be patient.  ;-)

Please note that modications should follow these coding guidelines:

- Indent is 4 spaces.
- Code should pass flake8 and pep257 linters.
- Vertical whitespace helps readability, don’t be afraid to use it.

Thank you for helping out!
