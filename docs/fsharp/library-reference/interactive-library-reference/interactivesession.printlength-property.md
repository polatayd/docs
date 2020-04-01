---
title: InteractiveSession.PrintLength Property
description: InteractiveSession.PrintLength Property
ms.date: 02/26/2020
---

# InteractiveSession.PrintLength Property

Gets or sets the total print length, the number of elements to display when printing collection values, in the interactive session.

**Namespace/Module Path:** Microsoft.FSharp.Compiler.Interactive

**Assembly:** FSharp.Compiler.Interactive.Settings (in FSharp.Compiler.Interactive.Settings.dll)

## Syntax

```fsharp
// Signatures:
member this.PrintLength :  int
member this.PrintLength : int with set :  int

// Usage:
interactiveSession.PrintLength
interactiveSession.PrintLength <- printLength
```

#### Parameters
*printLength*
Type: [int](https://msdn.microsoft.com/library/025d5455-3622-4ea5-9573-3ecbd4ee1375)

The print length to set.

## Remarks
The default value is 100.

## See Also
[Interactive.InteractiveSession Class](Interactive.InteractiveSession-Class.md)

[Microsoft.FSharp.Compiler.Interactive Namespace](index.md)