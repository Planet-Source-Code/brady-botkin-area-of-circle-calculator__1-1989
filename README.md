<div align="center">

## \*\*Area Of Circle Calculator\*\*


</div>

### Description

This code allows the user to find the area of circle by clicking a command button and then typing in the radius of the circle. It is very helpful to anyone working on a calculator project. I am also coming out with area of triangle and square.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Brady Botkin](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/brady-botkin.md)
**Level**          |Unknown
**User Rating**    |3.0 (24 globes from 8 users)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[Math/ Dates](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/math-dates__1-37.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/brady-botkin-area-of-circle-calculator__1-1989/archive/master.zip)





### Source Code

```
' Step 1. Place a command button in your form and name it Command1 and make the
'caption Area Of A Circle.
' Step 2. Copy this code into the form...
Private Sub Command1_Click()
 Dim Radius
 Radius = InputBox("Type In The Radius", "Radius")
 Dim Area
 Area = 3.14 * (Radius * Radius)
 MsgBox Area, vbDefaultButton1, "Answer"
 Dim Answer
End Sub
```

