<div align="center">

## A HIGHLIGHTED LABEL


</div>

### Description

This code was publshed before, but this is a much simpler way. This code is very cool! When you move a mouse over a label, the text lights up! When you move your mouse off of the label, the text turns back to its original color. VERY COOL, VERY EASY!
 
### More Info
 
Follow these easy directions (o:

1) Start up a new project in your Vb.

2)Make a label. It doesn't matter what you change the caption to, but keep the text color black!


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[SeeD](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/seed.md)
**Level**          |Unknown
**User Rating**    |3.2 (45 globes from 14 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__1-1.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/seed-a-highlighted-label__1-2847/archive/master.zip)





### Source Code

```
'Put this into the Form_MouseMove.
 Private Sub Form_MouseMove(Button As Integer, Shift As Integer, X As Single, Y As Single)
 Label1.ForeColor = &H80000012&
 End Sub
'Ok, now stick this part into your Labels Label1_MouseMove
Private Sub Label1_MouseMove(Button As Integer, Shift As Integer, X As Single, Y As Single)
 Label1.ForeColor = &H000000FF&
End Sub
```

