# ProfileApplicationSourceDetails Class
 

Holds details about an installation that is to be used to install app before Profiling.


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;<a href="T_Citrix_SDK_AppDNA_InstallCaptureSourceDetails">Citrix.SDK.AppDNA.InstallCaptureSourceDetails</a><br />&nbsp;&nbsp;&nbsp;&nbsp;Citrix.SDK.AppDNA.ProfileApplicationSourceDetails<br />
**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public class ProfileApplicationSourceDetails : InstallCaptureSourceDetails
```

###VB
```vbnet
Public Class ProfileApplicationSourceDetails
	Inherits InstallCaptureSourceDetails
```

The ProfileApplicationSourceDetails type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ProfileApplicationSourceDetails__ctor">ProfileApplicationSourceDetails</a></td><td>
Initializes a new instance of the ProfileApplicationSourceDetails class.</td></tr></table>&nbsp;
<a href="#profileapplicationsourcedetails-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_InstallCaptureSourceDetails_DriveLetter">DriveLetter</a></td><td>
Gets or sets a value that will be used to map a drive to the <a href="P_Citrix_SDK_AppDNA_InstallCaptureSourceDetails_InstallWorkingDirectory">InstallWorkingDirectory</a> before executing the <a href="P_Citrix_SDK_AppDNA_InstallCaptureSourceDetails_InstallCommand">InstallCommand</a>. This is only used by some Execution Profiles.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_InstallCaptureSourceDetails">InstallCaptureSourceDetails</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_InstallCaptureSourceDetails_InstallCommand">InstallCommand</a></td><td>
Gets or sets a value that is the command used by the execution profile to install the application.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_InstallCaptureSourceDetails">InstallCaptureSourceDetails</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_InstallCaptureSourceDetails_InstallWorkingDirectory">InstallWorkingDirectory</a></td><td>
Gets or sets a value that will be the working directory of the <a href="P_Citrix_SDK_AppDNA_InstallCaptureSourceDetails_InstallCommand">InstallCommand</a>.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_InstallCaptureSourceDetails">InstallCaptureSourceDetails</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_InstallCaptureSourceDetails_LoadSourceFile">LoadSourceFile</a></td><td>
Gets or sets a value that determines whether the file that is loaded into AppDNA is the output of the Install Capture execution profile or the file at <a href="P_Citrix_SDK_AppDNA_InstallCaptureSourceDetails_SourceFilePath">SourceFilePath</a>.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_InstallCaptureSourceDetails">InstallCaptureSourceDetails</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_InstallCaptureSourceDetails_ProductManufacturer">ProductManufacturer</a></td><td>
Gets or sets a value that will be the product manufacturer. This is only used by some Execution Profiles such as the AppV Sequencing profiles.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_InstallCaptureSourceDetails">InstallCaptureSourceDetails</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_InstallCaptureSourceDetails_ProductName">ProductName</a></td><td>
Gets or sets a value that will be the product name. This is only used by some Execution Profiles such as the AppV Sequencing profiles.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_InstallCaptureSourceDetails">InstallCaptureSourceDetails</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_InstallCaptureSourceDetails_ProductVersion">ProductVersion</a></td><td>
Gets or sets a value that will be the product version. This is only used by some Execution Profiles such as the AppV Sequencing profiles.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_InstallCaptureSourceDetails">InstallCaptureSourceDetails</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_InstallCaptureSourceDetails_SourceFilePath">SourceFilePath</a></td><td>
Gets or sets a value that is full path to the installation media.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_InstallCaptureSourceDetails">InstallCaptureSourceDetails</a>.)</td></tr></table>&nbsp;
<a href="#profileapplicationsourcedetails-class">Back to Top</a>

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
<a href="#profileapplicationsourcedetails-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />