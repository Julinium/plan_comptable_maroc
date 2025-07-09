# Plan Comptable Maroc

Latest version of Morocco Chart of Accounts (Plan Comptable). The file *pcm.txt* is a raw text where relationships between accounts is represented by simple indentations. The *pcm.json* is a list of **nested JSON objects** representing the **hierarchial tree of the accounts**. I made this repo because I needed the pcm.json file for my own development purposes and I am making it public in hope it may be useful to someone some day.
## Formatting
The keys of pcm.json are *code*, *name*, *translations* and eventually *children*. The *translations* values are a json object with language codes as the keys and translated litterals as values. French translation is redundant here because its litterals are the same as the values of the *name* keys. It is kept for standarization.
| code | name   | translations | children |
|--------|-----|---------|---------|
| 1  | COMPTES DE FINANCEMENT PERMANENT  |             "fr": "Comptes de financement permanent", "en": "Permanent Financing Accounts", "ar": "حسابات التمويل الدائم"| {<*Nested Children Accounts* with the same format>} |
| ... | ... | ... | ... |

For reference, top level accounts (with one single digit code may be called **Classes**.)
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
