```
  _____                         __               ____ ____
 / ___/__  __ _  __ _  ___  ___/ /__  _______   / __// / /
/ /__/ _ \/  ' \/  ' \/ _ \/ _  / _ \/ __/ -_) / _ \/_  _/
\___/\___/_/_/_/_/_/_/\___/\_,_/\___/_/  \__/  \___/ /_/  
```

# c64basic
Hacking on http://fssnip.net/le by Phillip Trelford to turn it into Commodore64 Basic.

For personal fun...

## Work in progress
_Code is in a messy state full of comments._

```fsharp
open Interpreter

let c64basic = """
5 GOTO 20
10 PRINT "SKIPPED"
20 FOR A = 1 TO 20
30 PRINT A
40 NEXT
"""

execute c64basic
```
