# ReportConfigurationService.AnalyzeAsync Method (IEnumerable(ReportConfiguration), IEnumerable(Application), IEnumerable(OSPatch))
 

Triggers an analysis of the specified applications and patches against this <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public Task<Analysis> AnalyzeAsync(
	IEnumerable<ReportConfiguration> reportingConfigurations,
	IEnumerable<Application> applications,
	IEnumerable<OSPatch> patches
)
```

###VB
```vbnet
Public Function AnalyzeAsync ( 
	reportingConfigurations As IEnumerable(Of ReportConfiguration),
	applications As IEnumerable(Of Application),
	patches As IEnumerable(Of OSPatch)
) As Task(Of Analysis)
```


#### Parameters
&nbsp;<dl><dt>reportingConfigurations</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">System.Collections.Generic.IEnumerable</a>(<a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>)<br />The collection of report configurations with which to analyze the applications.</dd><dt>applications</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">System.Collections.Generic.IEnumerable</a>(<a href="T_Citrix_SDK_AppDNA_Application">Application</a>)<br />The collection of applications to analyze.</dd><dt>patches</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">System.Collections.Generic.IEnumerable</a>(<a href="T_Citrix_SDK_AppDNA_OSPatch">OSPatch</a>)<br />The collection of patches to analyze.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/dd321424" target="_blank">Task</a>(<a href="T_Citrix_SDK_AppDNA_Analysis">Analysis</a>)<br />An <a href="T_Citrix_SDK_AppDNA_Analysis">Analysis</a> object which can be used to track the progress of the analysis.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ReportConfigurationService">ReportConfigurationService Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_ReportConfigurationService_AnalyzeAsync">AnalyzeAsync Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />