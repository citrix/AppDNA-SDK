# XenAdoptionMergedReportedApplication Class
 

Represents collection of <a href="T_Citrix_SDK_AppDNA_ReportedApplication">ReportedApplication</a> and aggregates data from it


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;<a href="T_Citrix_SDK_AppDNA_Solutions_Xen_Common_MergedReportedApplication">Citrix.SDK.AppDNA.Solutions.Xen.Common.MergedReportedApplication</a><br />&nbsp;&nbsp;&nbsp;&nbsp;Citrix.SDK.AppDNA.Solutions.XenAdoption.XenAdoptionMergedReportedApplication<br />
**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_XenAdoption">Citrix.SDK.AppDNA.Solutions.XenAdoption</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.XenAdoption (in Citrix.SDK.AppDNA.Solutions.XenAdoption.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public class XenAdoptionMergedReportedApplication : MergedReportedApplication
```

###VB
```vbnet
Public Class XenAdoptionMergedReportedApplication
	Inherits MergedReportedApplication
```

The XenAdoptionMergedReportedApplication type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_Xen_Common_MergedReportedApplication_AfterActionRag">AfterActionRag</a></td><td>
Gets the rag that would apply after any actions for triggered algorithms have been taken.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_Solutions_Xen_Common_MergedReportedApplication">MergedReportedApplication</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_Xen_Common_MergedReportedApplication_AnalysisRag">AnalysisRag</a></td><td>
Gets the analysis rag for this application, taking into account analysis only.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_Solutions_Xen_Common_MergedReportedApplication">MergedReportedApplication</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_Xen_Common_MergedReportedApplication_CustomizedRag">CustomizedRag</a></td><td>
Gets the customized rag for this application, taking into account analysis and customizations.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_Solutions_Xen_Common_MergedReportedApplication">MergedReportedApplication</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_Xen_Common_MergedReportedApplication_OverallRag">OverallRag</a></td><td>
Gets the overall rag for this application, taking into account analysis, external data and customizations.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_Solutions_Xen_Common_MergedReportedApplication">MergedReportedApplication</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_Xen_Common_MergedReportedApplication_ReportedApplications">ReportedApplications</a></td><td>
Gets the collection original <a href="T_Citrix_SDK_AppDNA_ReportedApplication">ReportedApplication</a> before merge.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_Solutions_Xen_Common_MergedReportedApplication">MergedReportedApplication</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_Xen_Common_MergedReportedApplication_ResultsByAlgorithm">ResultsByAlgorithm</a></td><td>
Gets a collection that holds the report data of this application for each algorithm in the report.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_Solutions_Xen_Common_MergedReportedApplication">MergedReportedApplication</a>.)</td></tr></table>&nbsp;
<a href="#xenadoptionmergedreportedapplication-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Equals</a></td><td>
Determines whether the specified object is equal to the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/4k87zsw7" target="_blank">Finalize</a></td><td>
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">GetHashCode</a></td><td>
Serves as a hash function for a particular type.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td>
Gets the <a href="http://msdn2.microsoft.com/en-us/library/42892f65" target="_blank">Type</a> of the current instance.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a" target="_blank">MemberwiseClone</a></td><td>
Creates a shallow copy of the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td>
Returns a string that represents the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr></table>&nbsp;
<a href="#xenadoptionmergedreportedapplication-class">Back to Top</a>

## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Protected field](media/protfield.gif "Protected field")</td><td><a href="F_Citrix_SDK_AppDNA_Solutions_Xen_Common_MergedReportedApplication__storage">_storage</a></td><td>
Internal collection of the applications in order to compose on any Rag getting
 (Inherited from <a href="T_Citrix_SDK_AppDNA_Solutions_Xen_Common_MergedReportedApplication">MergedReportedApplication</a>.)</td></tr></table>&nbsp;
<a href="#xenadoptionmergedreportedapplication-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Citrix_SDK_AppDNA_Solutions_XenAdoption">Citrix.SDK.AppDNA.Solutions.XenAdoption Namespace</a><br />