linter-pyflakes
=========================

This linter plugin for [Linter](https://github.com/AtomLinter/Linter) provides an interface to [pyflakes](https://launchpad.net/pyflakes). It will be used with python files.

## Installation
Linter package must be installed in order to use this plugin. If Linter is not installed, please follow the instructions [here](https://github.com/AtomLinter/Linter).

### pyflakes installation
Before using this plugin, you must ensure that `pyflakes` is installed on your system. To install `pyflakes`, do the following:

1. Install [pyflakes](https://launchpad.net/pyflakes) by typing the following in a terminal:
   ```
   pip install pyflakes
   ```

Now you can proceed to install the linter-pyflakes plugin.

### Plugin installation
```
$ apm install linter-pyflakes
```

## Settings
You can configure linter-pyflakes by editing ~/.atom/config.cson (choose Open Your Config in Atom menu):
```
'linter-pyflakes':
  'pyflakesExecutablePath': null #scss-lint path. run 'which scss-lint' to find the path
```

## Contributing
If you would like to contribute enhancements or fixes, please do the following:

1. Fork the plugin repository.
1. Hack on a separate topic branch created from the latest `master`.
1. Commit and push the topic branch.
1. Make a pull request.
1. welcome to the club

Please note that modications should follow these coding guidelines:

- Indent is 2 spaces.
- Code should pass coffeelint linter.
- Vertical whitespace helps readability, don’t be afraid to use it.

Thank you for helping out!

## Changelog
* **0.0.6** New linter API support

## Donation
[![Share the love!](https://chewbacco-stuff.s3.amazonaws.com/donate.png)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=KXUYS4ARNHCN8)
