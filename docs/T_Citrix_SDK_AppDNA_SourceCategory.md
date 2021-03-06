# SourceCategory Enumeration
 

Specifies the type of the application source that was used on import.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public enum SourceCategory
```

###VB
```vbnet
Public Enumeration SourceCategory
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:Citrix.SDK.AppDNA.SourceCategory.Packaged">**Packaged**</td><td>0</td><td>The application was a pre-packaged msi or other format that was directly imported.</td></tr><tr><td /><td target="F:Citrix.SDK.AppDNA.SourceCategory.Cached">**Cached**</td><td>1</td><td> **Obsolete. **(This enumeration value has been deprecated.) The imported msi was the cached msi that was captured during an install capture.</td></tr><tr><td /><td target="F:Citrix.SDK.AppDNA.SourceCategory.Snapshot">**Snapshot**</td><td>2</td><td>The msi that was loaded is the result of a snapshot. Snapshotted msi's are treated differently to packaged msi's since the componentisation is not considered authoritative from the manufacturer.</td></tr><tr><td /><td target="F:Citrix.SDK.AppDNA.SourceCategory.Stub">**Stub**</td><td>3</td><td>The application is not loaded yet, an application stub may be created</td></tr><tr><td /><td target="F:Citrix.SDK.AppDNA.SourceCategory.WebApplication">**WebApplication**</td><td>4</td><td>The msi that was loaded is the result of a web capture.</td></tr><tr><td /><td target="F:Citrix.SDK.AppDNA.SourceCategory.Unknown">**Unknown**</td><td>5</td><td>Unknown source category.</td></tr></table>

## See Also


#### Reference
<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />