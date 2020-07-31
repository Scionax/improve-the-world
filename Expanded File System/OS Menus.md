
## OS Menus, .os-menu Directory
A .os-menu is a common directory type that allows easy creation of OS navigation menus. These menus can be stored as icons on a user's desktop, utility bar, inside folders, etc.

When you open on a .os-menu, generally by clicking it, a navigation menu will open similar to a right-click menu.

The essential files within a .os-menu are the Metadata.config file (to assign an icon and simple details) and a .menu-contents shelf.
	
The .menu-contents shelf contains an ordered list of the following file types:

	.divider: Creates a menu divider at its given index position. Has an optional title.
	.os-menu: Creates a sub-menu within the parent menu.
	.url: Loads a designated website. Must provide a title, url, and icon.
	.directory: Opens a designated directory in a file explorer.
	.program: Launches a designated program. Automatically use the program metadata to fill in title, icon, etc.
	.script: Runs a designated .script file. Must provide a title, and an optional icon.
