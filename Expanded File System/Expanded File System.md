
## Advantages of the EFS (Expanded File System)
* Significantly better organization and navigation.
* Is essentially the file system equivalent of being Strictly Typed.
* Many opportunities for optimizations.
* Better error handling. Far easier to ensure proper handling of files.
* Can immediately identify missing or required content.
* Content becomes modular, reducing the complexity of working with each piece.
* Consistency in settings, configs, and other file archetypes across the system.

## Expanded Directories
* Directories have types, allowing them to apply additional rules to their sub-directories and files.
* By applying rules to directories, content becomes far easier to work with, organize, and utilize in readers and editors.
* Directories can restrict the types of files and directories allowed.
* A directory can be designated as a "Shelf".
	* Shelves have ordered content, and the order of content within a shelf is important.
		* Example: a "Code Sequence" shelf contains scripts that run in their assigned order.
		* Example: a book shelf can assign order to its books in a series.
		* Example: a book directory can contain a "Chapter" shelf that assigns order to its chapters.
	* All content in a shelf has a dynamically-identified index based on its current position in the shelf.
* A directory can have "Required Files" that it expects to be present.
	* If a Required File is not present, a ghost file (a semi-transparent stand-in) will appear.
	* This makes it very easy to identify and generate errors for malformed directories.
* A directory can have "Suggested Files" designated.
	* These files are optional, and will not cause errors if not present.
	* If a Suggested File is not present, it will show as a semi-transparent file in the directory.
* A directory can decide to designate "Allowed Types".
	* If a directory has this setting enabled, only the allowed file types and directory types can be added to it.
* A directory can have "Required Directories" and "Suggested Directories".
	* These behave like "Required Files" and "Suggested Files", but with directories instead of files.
* The rules that govern the behaviors of a directory type are assigned and enforced by the OS.
