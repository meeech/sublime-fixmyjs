# sublime-fixmyjs

> Sublime plugin to correct JS linting issues

You shouldn't have to care about linting issues. Now you don't have to using [fixmyjs](https://github.com/jshint/fixmyjs).

## Preview

![](http://i.imgur.com/1NKUiu4.gif)

## Install

### Install from GitHub

1) Open the Command Palette *(Cmd+Shift+P)*

2) Select Package Control > Add Repository

![](http://i.imgur.com/Z381xzi.png)

3) Paste in https://github.com/addyosmani/sublime-fixmyjs

![](http://i.imgur.com/fDl4T3r.png)

4) BOOM.

### Package Control (coming soon)

Install `FixMyJS` with [Package Control](https://sublime.wbond.net) and restart Sublime.

**You need to have [Node.js](http://nodejs.org) installed.**  
Make sure it's in your $PATH by running `node -v` in your command-line.

## Getting started

In a js file, open the Command Palette *(Cmd+Shift+P)* and choose `FixMyJS`. You can alternatively create one or more selections before running the command to only fix those parts.

![](http://i.imgur.com/gLetSdK.png)


### Options

*(Preferences > Package Settings > FixMyJS > Settings - User)*

### Keyboard shortcut

You can also set up a keyboard shortcut to run the command by opening up "Preferences > Key Bindings - User" and adding your shortcut with the `fixmyjs` command.

Example:

```json
[
	{ "keys": ["alt+super+j"], "command": "fixmyjs" }
]
```


### Project settings

You can override the default and user settings for individual projects. Just add an `"FixMyJS"` object to the `"settings"` object in the project's `.sublime-project` file containing your [project specific settings](http://www.sublimetext.com/docs/3/projects.html).

Example:

```json
{
	"settings": {
		"FixMyJS": {

		}
	}
}
```

## Kudos

This plugin is based on the excellent [Autoprefixer plugin](https://github.com/sindresorhus/sublime-autoprefixer) by Sindre Sorhus.


## License

MIT © [Addy Osmani](http://addyosmani.com)
