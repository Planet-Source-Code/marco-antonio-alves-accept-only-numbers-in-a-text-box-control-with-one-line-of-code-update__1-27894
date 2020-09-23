<div align="center">

## Accept only numbers in a text box control with one line of code UPDATED \* MUST SEE\*


</div>

### Description

first, my apologies for my bad english. hehe.

i updated my code to accept only numbers in a textbox. removed the bug of the another code. sorry by the another. hehe. but this code work
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Marco Antonio Alves](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/marco-antonio-alves.md)
**Level**          |Beginner
**User Rating**    |4.0 (28 globes from 7 users)
**Compatibility**  |VB 6\.0
**Category**       |[Coding Standards](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/coding-standards__1-43.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/marco-antonio-alves-accept-only-numbers-in-a-text-box-control-with-one-line-of-code-update__1-27894/archive/master.zip)





### Source Code

```
type code bellow into a keypress event of a textbox control
KeyAscii = IIf(Not KeyAscii = 8 And Not IsNumeric(Chr(KeyAscii)), 0, KeyAscii)
```

