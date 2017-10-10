# epitech-clion
Epitech norm compliant configuration for CLion IDE.
This CLion configuration is made to be as compliant as possible with the Epitech norm.
If you have any suggestion please let me know.

# Installation

**Code Style**<br />
*file -> settings -> code style -> manage... -> import*
- Import "Epitech C 2017.xml"

**Epitech Header**<br />
*file -> settings -> code style -> File and Code Templates -> Includes*
- Add an include named "C Epitech Header" with extension 'h' and paste the content of Header_Template.txt in the large field.
- Replace the promo variable set by default to '2022' to your year of promo.
*file -> settings -> code style -> File and Code Templates -> Files*
-> C Source File replace "C File Header.h" by "C Epitech Header.h"
-> C Header File replace "C File Header.h" by "C Epitech Header.h"

# Known problems:
- When creating a new project, the default main generated doesn't have the epitech header, you have to copy paste it manually.

# Warning
- The number of line in a function, line breaks != number of lines, more exactly 19 line breaks = 20 lines.
- When including header, check that CLion didnt put the include before the Epitech Header.

# Old Installation

**Code Style**<br />
*file -> settings -> code style -> manage... -> import*
- Import "Epitech_C_old.xml"

**Epitech Header**<br />
*file -> settings -> code style -> File and Code Templates -> Includes*
- Add an include for c/h Extension and paste the content of Header_Template_old.txt in it.
- Replace 'nom' and 'prenom' with yours.

# Old Known problem:
- When reformating the file, variable and function aren't aligned together, you have to do it manually.
- The header is semi-hard coded since there isn't a "PATH" variable and the last modified field isn't updated. (but it shouldn't affect the norm)
- When creating a new project, the default main generated doesn't have the epitech header, you have to copy paste it manually.
- Be carefull when declaring a variable and a function, Clion automatically put a space instead of a tab, you have to fix it manually.
