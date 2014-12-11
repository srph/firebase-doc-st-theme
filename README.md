firebase-doc-st-theme
=====================

A fail imitation of the color scheme of Firebase documentation code block for Sublime Text 3, built with [THTheme editor](https://github.com/aziz/tmTheme-Editor) by [@aziz](https://github.com/aziz/).

### Installation

Unfortunately, I am too busy to create this as a [sublime package](https://sublime.wbond.net/). However, you may manually install.

1. Download the [zip](https://github.com/srph/firebase-doc-st-theme/archive/master.zip).
2. Extract ```Firebase API.tmTheme``` to your packages folder (Main Menu, ```Preferences``` (tab) -> ```Browse Packages```).
3. Open up your ```user``` settings (Main Menu, ```Preferences``` (tab) -> ```Settings - User```).
4. Set the ```color_scheme``` property to ```Packages/Firebase API.tmTheme```

```json
// Preferences.sublime-settings

{
	// trimmed for brevity
	// your other settings
	"color_scheme": "Packages/Firebase API.tmTheme"
}

```
