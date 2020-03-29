# My Sublime Text 3

I am currently using [Sublime Text 3](https://www.sublimetext.com/3). I've also been using [VSCode](https://code.visualstudio.com/) for quite a while. They are both really good editors, but I experienced Sublime Text being a bit snappier and it's the overall minimalistic UI I do prefer more.

## My User Settings

These are my personal `User settings`. You can access the setting quickly by typing `cmd + ;` on Mac or `ctrl + ;` on windows maschines.

```json
{
	"color_scheme": "Packages/Color Scheme - Default/Mariana.sublime-color-scheme",
	"folder_exclude_patterns":
	[
		".svn",
		".git",
		".hg",
		"CVS",
		"*/node_modules"
	],
	"font-face": "Source Code Pro",
	"font_options": [
		"gray_antialias"
	],
	"font_size": 16,
	"highlight_line": true,
	"highlight_modified_tabs": true,
	"ignored_packages":
	[
		"Vintage"
	],
	"remember_open_files": false,
	"spell-check": true,
	"theme_font_options":
	[
		"gray_antialias"
	]
}
```

## My Plugins

The following shows a list of plugins that I personally use.

- [BracketHighlighter](https://packagecontrol.io/packages/BracketHighlighter): As the name says, it highlights the brackets such as `[]`, `{}` in your code which is pretty helpful.

- [DocBlockr](https://packagecontrol.io/packages/DocBlockr) is pretty convenient in terms of API documentation. Just type `/**` then the *Enter*-key and the parameters are parsed and some documentation is added automatically.

- [ESLint](https://packagecontrol.io/packages/ESLint) & [SublimeLinter-jshint](https://packagecontrol.io/packages/SublimeLinter-jshint)

- [FileIcons](https://packagecontrol.io/packages/FileIcons) brings some nicer and colored icons for Sublime Text.

- [GitGutter](https://packagecontrol.io/packages/GitGutter) adds diff hints to the gutter of the sidebar. By hovering over the indicators, you can see the code changes appearing in a popup.

- [MarkdownPreview](https://packagecontrol.io/packages/MarkdownPreview) is a great plugin for previewing and building your markdown files in the web browser.

- [Package Control](https://packagecontrol.io/packages/Package%20Control) is a pretty convenient plugin, that enables the easy installation of plugins in Sublime Text. To install packages you simply type `cmd+shift+p` on Mac to open the Command Palette and just type `Install Package` and enter the package name of the package you want to install. The list of packages can be found on the Package Control website.

- [SideBarEnhancements](https://packagecontrol.io/packages/SideBarEnhancements) provides the ability to right-click files and folders to open a context menu providing *"Open with..."*, *"Copy"* and *"Paste"* functionality.

- [SublimeCodeIntel](https://packagecontrol.io/packages/SublimeCodeIntel) is a must have plugin which provides code intelligence and autocompletion.

- [TrailingSpaces](https://packagecontrol.io/packages/TrailingSpaces) is a plugin that highlights and removes trailing whitespaces. I personally use  the highlighting feature only.
