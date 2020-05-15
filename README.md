# PL/B for Visual Studio Code

An extension for VS Code which provides support for the Programming Language for Business (PL/B).

This extension supports the Sunbelt Computer Software version of the PL/B language. 

Supports:
* Syntax highlighting
* Code Folding
* Code snippets

### Select PL/B as a language
* On the bottom-right corner, click on the *select language mode* button, if you have created a new file it should display *Plain Text*
* Select *PLB* in the list of languages.

Alternatively, saving the file with a `.pls`, `.plbs`, or `.dbs` extension, will allow VS Code to understand that it is a PL/B file, and automatically select the language correctly.

### Using snippets
* Bring-up the *autocomplete* menu by hitting the `Ctrl+Shift` key combination
* Select the snippet that you want to use in the list
* Use `tab` to navigate trough the snippet's variables

### Change the file encoding

The default file format is UTF8, and you might want to change this for PL/B. To do this just:

1. Click on 'Programming Language for Business' at the right side of the bottom status bar 
2. Select: Configure 'Programming Language for Business' language settings. This should bring up the settings.json file for editing.
3. Find and click on files.encoding
4. Select the new default encoding such as windows1252 or CP437 (DOS). The settings.json file will now have the following section:

	"[plb]": {
		"files.encoding": "windows1252",
		},
		
5. Save and close the settings.json file.

