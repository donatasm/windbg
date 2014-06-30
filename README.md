windbg
======

Debugging .NET workflow using windbg

1. `c:\> set _NT_SYMBOL_PATH=SRV*C:\WINDOWS\Symbols*http://msdl.microsoft.com/download/symbols` before starting windbg.

2. `.loadby sos clr`

3. `.load E:\psscor4\amd64\psscor4.dll` [Download here](http://www.microsoft.com/en-us/download/details.aspx?id=21255).

4. `.load E:\sosex_64\sosex.dll`

5. Run `!analyze -v` first!

6. [windbg command reference for .NET](https://docs.google.com/document/d/1yMQ8NAQZEBtsfVp7AsFLSA_MkIKlYNuSowG72_nU0ek).

7. Find deadlocks: `!dlk`
