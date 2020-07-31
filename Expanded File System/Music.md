Note: This specification should be reviewed and updated by someone more familiar with MIDI 2.0 internals. I have provided an outline that will greatly improve the navigational abilities of MIDI 2.0, but the remaining essence of MIDI 2.0 should be synchronized with EFS for this specification to be complete.

## .music Directory
A .music directory tracks roughly the same data as MIDI 2.0, but is accessible by standard navigation with a cleaner structure. This makes it easy for anyone to review it without having to launch an editor or interpret a file format.

The contents of a .music directory include:
* /tracks: A sub-directory that contains .track sub-directories each musical track in the composition.
	* /{instrument}
	* /{percussion}
	* /{sound effects}
	* /{etc}
* Composition: The final composition rules for the music.
