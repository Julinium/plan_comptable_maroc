# Plan Comptable Maroc
Tree-structured **Moroccan Chart of Accounts** (Plan Comptable Maroc, pcm). 
I made this repo because I needed the pcm.json file for my own development purposes and I am making it public in hope it may be useful to someone.
- The file *pcm.txt* is a raw text where relationships between accounts is represented by simple indentations.
- The *pcm.json* is a list of **nested JSON objects** representing the **hierarchial tree of the accounts**.
## Formatting
The keys of pcm.json are *code*, *name*, *translations* and eventually *children*. 
- The *children* value, if present, is a list of json objects structured exactly the same way as parent.
- The *translations* value is a json object with language codes as keys and translated litterals as values. French translation is redundant here because its litterals are the same as the values of the *name* keys. It is kept for standarization.
- For reference, top level accounts (with one single digit code may be called **Classes**.)
## Some useful resoning:
- An account is a leaf if it has no *children* key.
- An account is a root account (known as a Class) if its *code* is one digit (0-9).
## Translations
Main names are in French. Translations are provided in three languages: French, English and Arabic. 
Arabic and English were translated using AI and may contain errors or inaccuracies.

## Copyright and Licence
© 2025 julinium. Licensed under the **GNU GPL-2** licence. Please see [LICENCE](https://github.com/Julinium/plan_comptable_maroc/blob/main/LICENSE) file for details. 

- **Conditions**
  - You must include the original license and copyright.
  - You must clearly state any changes you make.
  - You must provide the source code when distributing the software.
  - You must release derivative works under the same GPL-2 license.

- **Permissions**
  - You can use the software commercially.
  - You can modify the software.
  - You can distribute the software.
  - You can use the software privately.

- **Limitations**
  - There is no liability for damages.
  - The software is provided without any warranty.
## Credits:
Some data was taken from [Adil Hadri's website](https://plancomptable.ma/). Thanks to him.
- Note to Adil: I could not find any terms on your website and since the data it presents is publicly available elsewhere, I supposed your work is public domain. If that's not the case, please let me know what your policy or license is and I will comply.
