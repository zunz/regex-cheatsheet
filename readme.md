Regex Cheatsheet
========================

### Wilcard: .

### Character Set: [ ]

Metacharacters di dalam charset:

- range: **-**

  **[0-9]** artinya **[0123456789]**

- not: **^** 

  **[^0-9]** artinya selain digit

### Shorthand

- **\d** digit, alias **[0-9]**
- **\w** word characters alias **[0-9a-zA-Z_]** (termasuk underscore)
- **\s** whitespace (space, tab)
- **\D** bukan digit
- **\W** bukan word characters
- **\S** bukan whitespace

### Repetisi

- Satu atau lebih: **+**

- Nol atau lebih: **\***

- Nol atau satu: **?**

- Exactly: **{ }**

  {2} artinya repetisi 2 kali

  {2, 4} artinya repetisi 2 sampai 4 kali

  {2, } artinya repetisi 2 sampai habis

- Lazy (mengambil paling sedikit, lawan dari greedy): ?

  misal: a*? 

### Awal text: ^

### Akhir text: $

### Group: ( )

Menghindari backreference: **(?:....)**

### OR: |

### Boundary: \b
