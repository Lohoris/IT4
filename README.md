IT4 keyboard layout
===

Overview
--------

This is an alternative layout for the Italian keyboard, but its principles may be easily adapted to other languages.

It is aimed both at fixing some **generic language problems** with the original layout, and at helping **developers** reach more easily the symbols they need.

### Letters

* `é` reachable with a single stroke, on `+`
* `È` reachable on `shift`+`è`
* `î` reachable on `opt`+`shift`+`ì`

Those letters are either misplaced or totally absent in the traditional layout.

### Symbols

Like in some ancient keyboards, you reach the numbers using `shift` (or `capslock`), while the unmodified key outputs a symbol.

* `&` on `1`
* `"` on `2`
* `$` on `3`
* `{` on `4`
* `}` on `5`
* `-` on `6`
* `/` on `7`
* `(` on `8`
* `)` on `9`
* `=` on `0`
* `+` on `shift`+`+`
* `%` on `shift`+`ò`
* `*` on `shift`+`à`
* `!` on `shift`+`,`
* `;` on `-`
* `…` on `opt`+`,`
* `•` on `opt`+`.`
* `°` on `opt`+`-`

### Deadkeys

* long vowel on `opt`+`7`
* diaeresis on `opt`+`u`
* acute accent on `opt`+`8`
* grave accent on `opt`+`9`
* circumflex on `opt`+`ì`

### Full map

I suggest you look at the full map using [Ukelele](http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=ukelele), but here it is anyway.

#### plain
`\` `&` `"` `$` `{` `}` `-` `/` `(` `)` `=` `'` `ì`

`tab` `q` `w` `e` `r` `t` `y` `u` `i` `o` `p` `è` `é`

`caps` `a` `s` `d` `f` `g` `h` `j` `k` `l` `ò` `à` `ù`

`lshift` `<` `z` `x` `c` `v` `b` `n` `m` `,` `.` `;`

#### shift
`|` `1` `2` `3` `4` `5` `6` `7` `8` `9` `0` `?` `^`

`tab` `Q` `W` `E` `R` `T` `Y` `U` `I` `O` `P` `È` `+`

`caps` `A` `S` `D` `F` `G` `H` `J` `K` `L` `%` `*` `§`

`lshift` `>` `Z` `X` `C` `V` `B` `N` `M` `!` `:` `_`

#### opt
`bt`  ` `  ` `  ` `  `¢` `~`  ` `  `Dl` `D'` `Dg` `ç` `¡` `D^`

`tab`  ` `  ` `  `€` `®` `™`  ` `  `D¨`  ` `  ` `  `π` `[` `]`

`caps` `α` `ß` `δ`  ` `  `γ`  ` `  ` `  ` `  `£` `@` `#`  ` `

`lshift` `≤`  ` `  `†` `©`  ` `  `β` `D˜` `µ` `…` `•` `°`

#### shift+opt
` `  ` `  ` `  ` `  ` `  ` `  ` `  ` `  ` `  ` `  ` `  `¿` `î`

`tab`  ` `  ` `  ` `  ` `  ` `  ` `  ` `  ` `  ` `  ` `  ` `  ` `

`caps`  ` `  ` `  `Δ`  ` `  ` `  ` `  ` `  ` `  ` `  `‰` `—` `¶`

`lshift` `≥`  ` `  ` `  ` ` ` `  ` `  ` `  ` `  ` `  `·` `–`

#### capslock
`\` `1` `2` `3` `4` `5` `6` `7` `8` `9` `0` `'` `Ì`

`tab` `Q` `W` `E` `R` `T` `Y` `U` `I` `O` `P` `È` `É`

`caps` `A` `S` `D` `F` `G` `H` `J` `K` `L` `Ò` `À` `Ù`

`lshift` `<` `Z` `X` `C` `V` `B` `N` `M` `,` `.` `;`

Platforms
---------

This is the OSX version.
I did create partial Linux and Windows ports: if anyone is interested in completing them and keeping them up-to-date feel free to contact me.

Installation
------------

1. copy the file `IT4.keylayout` into `/Library/Keyboard Layouts` or `~/Library/Keyboard Layouts`
2. logout
3. login
4. open "System Preferences" / "Language & Text" / "Input Sources"
5. search for "IT4 Keyboard Layout" and check the box
6. check also "Show Input menu in menu bar"
7. go into the menu bar and select "IT4 Keyboard Layout"

_Steps 2 and 3 were necessary in older OSX versions, while may not be required anymore in modern ones._
