Sublime Starter Settings and Configuration
===============================================
The Preferences.sublime-settings file is where a user will place all their personal settings to override the Sublime Text defaults. 
Copying and pasting this Preferences.sublime-settings file into the Sublime settings will provide the Basic Settings below.
  
For more information, visit the [corresponding article](http://scotch.io/bar-talk/x/sublime-text-starter-kit).
  
Instructions
-----------------------------------------------
1.  Install the UbuntuMono.ttf font to your computer
2.  Copy **or** Move Preferences.sublime-settings into Sublime User folder
  	- Copy file contents into: Preferences -> Settings - User
	- Move file into: Preferences -> Browse Packages

Included Settings
-----------------------------------------------
* 	Change the default font face to Ubuntu Mono
* 	Removed code folding buttons (super annoying to accidentally click those)
* 	Added rulers at 80 columns (good for programming and keeping code clean and short)
* 	Disabled tab completion
* 	Enabled Vim mode 
* 	Disabled slow plugin detection. This would show up when using Emmet or some other autocompletion plugin (may be fixed now)

### Uncomment to Enable These Settings
* Change the theme
* Opening a file starts in Vim mode
	
Package Manager Installations
-----------------------------------------------

Install these using the Package Manager provided by [Will Bond] (http://wbond.net/sublime_packages/package_control).

### Recommended Plugins
* Git (Read this to get Git working on Sublime Text in Windows)
* SFTP
* Alignment
* Emmet
* SideBarEnhancements
* AdvancedNewFile
* Bracket Highlighter
* Gist
* DocBlockr
 
### Recommended Themes
* Theme - Flatland
* Theme - Nexus
* Theme - Nil
* Theme - Soda
 
Theme Installation Instructions
-----------------------------------------------
Make sure that you install the theme using Package Manager before setting it in the Preferences.sublime-settings

1. 	Install using Package Manager
2. 	Edit Preferences.sublime-settings
3. 	Add this line:

	<code>"theme": "Nexus.sublime-theme"</code>

Color Scheme Instructions
----------------------------------------------
Dayle Rees has some great [color schemes](https://github.com/daylerees/colour-schemes) to choose from.

1. 	Download the theme files you want (.tmTheme)
2. 	Move .tmTheme files into Packages/User
3. 	Activate using Preferences -> Color Scheme -> User
