# Plan Comptable Maroc

Latest version of Morocco Chart of Accounts (Plan Comptable).
## Format
The pcm.json file is a list of a nested JSON objects with *code*, *name*, *translations* and eventual *children* keys, like:
| name   | code | translations | children |
|--------|-----|---------|---------|
| COMPTES DE FINANCEMENT PERMANENT  | 1  |             "fr": "Comptes de financement permanent", "en": "Permanent Financing Accounts", "ar": "حسابات التمويل الدائم"| {*Nested Children Accounts* with same format} |
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
