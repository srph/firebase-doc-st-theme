firebase-doc-st-theme
=====================

A (fail imitation) port for [Sublime Text 3](http://www.sublimetext.com/) of the color scheme of [Firebase documentation](https://www.firebase.com/docs/web/) code block, built with [THTheme editor](https://github.com/aziz/tmTheme-Editor) by [@aziz](https://github.com/aziz/).

### Screenies

![v0.0.1](http://i.imgur.com/uHe988W.png)

### Installation

Unfortunately, I am too busy to create this as a [sublime package](https://sublime.wbond.net/). However, you may manually install.

1. Download the [zip](https://github.com/srph/firebase-doc-st-theme/archive/master.zip).
2. Extract ```firebase-doc.tmTheme``` to your packages folder (Main Menu, ```Preferences``` (tab) -> ```Browse Packages```).
3. Open up your ```user``` settings (Main Menu, ```Preferences``` (tab) -> ```Settings - User```).
4. Set the ```color_scheme``` property to ```Packages/firebase-doc.tmTheme```

```js
// Preferences.sublime-settings

{
	/**
	 * trimmed for brevity
	 * your other settings here --
	 */
	"color_scheme": "Packages/firebase-doc.tmTheme"
}

```
