# ApplicationService.Get Method (ApplicationFilter, Object, Int32, Int32, ApplicationFilter)
 

Returns a collection of <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects that respects filtering and paging requirements.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public Collection<Application> Get(
	ApplicationFilter filterBy,
	Object filterValue,
	int count,
	int offset,
	ApplicationFilter orderBy
)
```

###VB
```vbnet
Public Function Get ( 
	filterBy As ApplicationFilter,
	filterValue As Object,
	count As Integer,
	offset As Integer,
	orderBy As ApplicationFilter
) As Collection(Of Application)
```


#### Parameters
&nbsp;<dl><dt>filterBy</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_ApplicationFilter">Citrix.SDK.AppDNA.ApplicationFilter</a><br />Specifies the field that *filterValue* is compared against to filter the results.</dd><dt>filterValue</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />Specifies a value that is used to filter the results if *filterBy*is not NONE.</dd><dt>count</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/td2s409d" target="_blank">System.Int32</a><br />The maximum number of <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects to return. Use -1 to retrieve all ReportedApplicationsBy that match the other parameters.</dd><dt>offset</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/td2s409d" target="_blank">System.Int32</a><br />This represents the number of results to skip.</dd><dt>orderBy</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_ApplicationFilter">Citrix.SDK.AppDNA.ApplicationFilter</a><br />This specifies a property of the <a href="T_Citrix_SDK_AppDNA_Application">Application</a> object by which to order the result set.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/ms132397" target="_blank">Collection</a>(<a href="T_Citrix_SDK_AppDNA_Application">Application</a>)<br />Returns a collection of the requested <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects.

## Remarks
The results are filtered, then ordered according to *orderBy*, then *offset* is applied, then *count* is applied, before returning the results.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ApplicationService">ApplicationService Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_ApplicationService_Get">Get Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />