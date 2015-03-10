Mathematica Auto-Backup Package
===============================

A Mathematica package to make up for Mathematica's abysmal built-in auto-save functionality. Once loaded, it will automatically backup any open notebook at user-defined intervals. Configurable, works well...

The package file, `NotebookBackup.m`, should be saved to the Mathematica user "Applications" folder; for Unix systems (including OS X) this is `~/.Mathematica/Applications`. In Windows Vista/7 it's something like `C:\\Users\\[you]\\AppData\\...` The package can then be loaded by entering ``<<NotebookBackup` `` into Mathematica. More instructions are inside the file; note that it may need to be configured for the particular system (paths, etc.) before being used. Mathematica 7+.
