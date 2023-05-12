# Creo Configuration Files

This project provides [Notepad++](https://notepad-plus-plus.org/) [UDL files](https://npp-user-manual.org/docs/user-defined-language-system/) for several configuration files of [PTC](https://www.ptc.com/)'s CAD system [Creo Parametric](https://www.ptc.com/en/products/creo/parametric) (formerly known as Pro/ENGINEER).

The benefit of using the UDL files is that you get [syntax highlighting](https://en.wikipedia.org/wiki/Syntax_highlighting) when editing the configuration files with Notepad++.

## Getting Started

### Download

The latest version of the UDL files can be downloaded from https://github.com/DonChunior/Creo-Configuration-Files/releases/latest.

### Installing

How to install a UDL file in Notepad++:

1. Download the asset "Source Code (zip)" from the previously mentioned link.
2. If it doesn't already exist, create a subfolder named *userDefineLangs* in the directory *%APPDATA%\Notepad++* (i.e. *C:\Users\\%USERNAME%\AppData\Roaming\Notepad++*).
3. Extract the *\*.xml* files of the UDLs you want into the just mentioned *userDefineLangs* folder.
4. After the next restart of Notepad++ the UDLs will be available.

For details see the chapters "[Import a UDL](https://npp-user-manual.org/docs/user-defined-language-system/#import-a-udl)" and "[UDL File Locations](https://npp-user-manual.org/docs/user-defined-language-system/#udl-file-locations)" in the Notepad++ User Manual.

### How to use the syntax highlighting

Once the UDL is imported into Notepad++ the following features are supported:

1. Creo config-files will automatically be detected based on file endings *\*.pro* and *\*.sup*.
2. Once a Creo config option is typed into Notepad++ it will be highlighted as bold blue text.
3. Alternatively, the config option will be highlighted as bold and italic light blue text for hidden config options.
4. If a config option is not highlighted, please check for typing errors and if you are using the correct version.
5. Comments start with an exclamation mark and are rendered as brown text.
6. Config-options can be grouped using the syntax `! =====` for opening and `! -----` for closing the group.

## Authors and acknowledgment

- Domenic Laritz, CAD system administrator at [Liebherr](https://www.liebherr.com/).
- Thanks to [Flo-R1der](https://github.com/Flo-R1der) for adding the possibility to group config.pro settings as well as the README chapter "[How to use the syntax highlighting]".

## License

This project is licensed under the terms of the Unlicense.
See the [LICENSE](./LICENSE) file for details.

## Acknowledgment

- Many thanks to [Olaf Corten](https://creosite.com/). The option lists on his website are the basis of most UDL files.
