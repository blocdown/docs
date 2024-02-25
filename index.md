Type each block on a seperate line.

## Syntax
### Blocks:
```
text|opcode|type
```

*:information_source: For labels you can leave the opcode section blank, but you **MUST** still include it*

***Example:***
```
current hour|hourNow|r
```

***Makes:***
![scratchblocks rendered version of (current hour)](./images/exampleblock.svg) with the opcode `hourNow`

*:information_source: The block's text can also include pipes (`|`)*

### Inputs:
```
[defaultValue|argName|type]
```
To add an argument to a block, just add the above in the block text.

*:information_source: For boolean, costume, and sound inputs you can leave the defaultValue section blank, but you **MUST** still include it*

*:information_source: The input's deafultValue can also include pipes (`|`), but it **CANNOT** contain `[` or `]`*

*:information_source: Buttons and labels cannot have inputs*

***Example:***
```
alert [hello|text|s]|alert|c
```
***Makes:***
![scratchblocks rendered version of `alert [hello]`](./images/exampleinputblock.svg) with the opcode `alert`


## Types
Specifies the type of block/input. These values are **NOT** case sensitive.
### Block types:
 - `r` or `reporter` ![scratchblocks rendered version of `(____`](./images/blocktype/reporter.svg)
 - `b`, `bool` or `boolean` ![scratchblocks rendered version of `<____`](./images/blocktype/boolean.svg)
 - `c` or `command` ![scratchblocks rendered version of `____`](./images/blocktype/command.svg)
 - `lb`, `lbl` or `label` ![screenshot of a label with the text "text"](./images/blocktype/label.jpg)
 - `bt`, `btn` or `button`![screenshot of a button with the text "text"](./images/blocktype/button.jpg)
### :warning: Special/Complicated blocks :warning:
These blocks will most likely require you to edit the generated extension for them to work properly
 - `h` or `hat` ![scratchblocks rendered version of `____::hat`](./images/blocktype/hat.svg)
 - `e` or `event` ![scratchblocks rendered version of `____::hat`](./images/blocktype/hat.svg)
 - `l` or `loop` ![scratchblocks rendered version of `____{`](./images/blocktype/loop.svg)
 - `cl` or `conditional` ![scratchblocks rendered version of `____{`](./images/blocktype/loop.svg)
### Input types
 - `s`, `str`, `t`, `txt`, `text` or `string` ![screenshot of a text input](./images/inputtype/text.jpg)
 - `no`, `num`, `#` or `number` ![screenshot of a number input](./images/inputtype/number.jpg)
 - `b`, `bool` or `boolean` ![screenshot of a boolean input](./images/inputtype/boolean.jpg)
 - `a`, `d`, `dir`, `direction` or `angle` ![screenshot of an angle input](./images/inputtype/angle.jpg)
 - `c` or `color` (or `colour` if you wish) ![screenshot of a color input](./images/inputtype/color.jpg)
 - `m` or `martrix` ![screenshot of a martrix input](./images/inputtype/martrix.jpg)
 - `n` or `note` ![screenshot of a note input](./images/inputtype/note.jpg)
 - `cm` or `costume` ![screenshot of a costume input](./images/inputtype/costume.jpg)
 - `sd` or `sound` ![screenshot of a sound input](./images/inputtype/sound.jpg)
 - `i`, `img` or `image`