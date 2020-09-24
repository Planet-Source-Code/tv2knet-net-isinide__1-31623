<div align="center">

## IsInIDE?


</div>

### Description

--IsInIDE()

--It'll return true if running in IDE
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[TV2kNET\.net](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/tv2knet-net.md)
**Level**          |Beginner
**User Rating**    |3.5 (14 globes from 4 users)
**Compatibility**  |VB 6\.0
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__1-1.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/tv2knet-net-isinide__1-31623/archive/master.zip)

### API Declarations

```
'none
```


### Source Code

```
Public Function IsInIDE() As Boolean
'-----------------------------------
'-  IsInIDE()
'-
'- It'll return true if running in IDE
'-
'-   By T-Virus Creations
'- http://www.tvirusonline.be
'- email: tvirus4ever@yahoo.co.uk
'-
'-----------------------------------
'-TESTED: In VB6.0 SP5
'-----------------------------------
Dim x As Long
On Error Resume Next
x = VB.App.LogMode()
If x = 1 Then IsInIDE = False Else IsInIDE = True
End Function
```

