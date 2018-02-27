# KSoft.Tools.TypeTools

1. Add package do Your project

```powershell
Install-Package KSoft.Tools.TypeTools
```

2. Use: 

```csharp
using System.Collections.Generic;
using KSoft.Tools.TypeTools;


public class Example
{
  public void method()
  {
     var extractor = new TypeExtractor();
     extractor.ProcessType(typeof(B));
     int typesCount= extractor.Types.Count;
  }
}
```