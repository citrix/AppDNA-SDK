# Import.GetOutputDirectory Method 
 

Returns the Output directory which is to contain install capture files, which is generated on the fly (with timestamp + application name).

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public string GetOutputDirectory(
	string path
)
```

###VB
```vbnet
Public Function GetOutputDirectory ( 
	path As String
) As String
```


#### Parameters
&nbsp;<dl><dt>path</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />This is the path to the installer which we want to retrieve the output directory of.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a><br />The specified output directory

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Import">Import Class</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />