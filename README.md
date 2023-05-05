# Creo Configuration Files

This project provides [Notepad++](https://notepad-plus-plus.org/) [UDL files](http://docs.notepad-plus-plus.org/index.php/User_Defined_Languages) for several configuration files of [PTC](https://www.ptc.com/)'s CAD system [Creo Parametric](https://www.ptc.com/en/products/cad/creo/parametric) (formerly known as Pro/ENGINEER).

The benefit of using the UDL files is that you get [syntax highlighting](https://en.wikipedia.org/wiki/Syntax_highlighting) when editing the configuration files with Notepad++.

## Getting Started

### Download

The latest version of the UDL files can be downloaded from https://github.com/DonChunior/Creo-Configuration-Files/releases/latest.

### Installing

How to install a UDL file in Notepad++:
1. If Notepad++ is open, select "Define your language" from the "Language" menu.
2. Click on the "Import" button in the dialog window "User-Defined".
3. Select the corresponding UDL file (*.xml) in the selection dialog and click on the button "Open".
4. Confirm the message box "Import successful" by clicking on the button "OK".
5. Follow the steps 2 to 4 to install more UDL files.
6. Close the dialog window "User-Defined" by clicking on the "X" at the top right corner.

### How to use the syntax highlighting

Once the UDL is imported into Notepad++ the following features are supported:
1. Creo config-files will automatically be detected based on file endings `*.pro` and `*.sup`.
2. Once a Creo config option is typed into Notepad++ it will be highlighted as bold blue text.
3. Alternatively, the config option will be highlighted as bold and italic light blue text for hidden config options.
4. If a config option is not highlighted, please check for typing errors and if you are using the correct version.
5. Comments start with an exclamation mark and are rendered as brown text.
6. Config-options can be grouped using the syntax `! =====` for opening and `! -----` for closing the group.


## Author

- Domenic Laritz, CAD system administrator at [Liebherr](https://www.liebherr.com/).

## License

This project is licensed under the terms of the Unlicense.
See the [LICENSE](./LICENSE) file for details.

## Acknowledgment

- Many thanks to [Olaf Corten](https://creosite.com/). The option lists on his website are the basis of most UDL files.
