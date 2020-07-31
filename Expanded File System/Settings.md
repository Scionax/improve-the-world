
## .settings Directory
* A .settings directory is one of the most common directory types.
* This directory is restricted by file type, only allowing .config files within it.
* Programs can load multiple .settings directories in a desired order, such as to load the default settings file and a user-specific settings file.
	* Newly loaded settings always update any previously loaded settings with the configurations it has set.

### .config Files
A .config file is a key/value set of configurations that can be added to a .settings directory. These files automatically open to editors designed for key/value editing with a consistent UI.

Each key/value pair in a .config file is formatted as key=value, and each pair must be on a new line. Keys are always strings.

There are several standard .config files, including:
* Metadata.config: Provides details about a program, such as title, icon, and other details.
* Audio.config: Provides configurations for a program's audio settings.
  * Master Volume
  * Sound Volume
  * Music Volume
  * Sound Muted
  * Music Muted
  * Speaker Configurations
  * Music Track Playlist Configurations
  * Program-Specific Audio Configurations
  * etc.
* Graphics.config: Provides configurations for a program's graphics settings.
  * Resolutions & Display Configurations
  * VSync Configurations
  * Brightness and Contrast Configurations
  * Program-Specific Graphics Configurations
  * etc.
* Controls.config: Provides configurations for managing inputs.
* Keyboard.config: Provides configurations specific to keyboard input.
* Mouse.config: Provides configurations specific to mouse input.
* Joypad.config: Provides configurations specific to joypad input.
* Shortcuts.config: Provides configurations for default and custom shortcuts in the program.
* Keybinds.config: Provides configurations for default and custom keybinds in the program.
* Repo.config: Provides configurations for a repository. Related to coding projects.
* Access.config: Provides configurations for access, such as parental controls, time limits, etc.
* Language.config: Provides configurations for languages.
* Additional custom configurations and more...

Programs can also create custom .config files, which are always assigned to scan the current .settings directory.
