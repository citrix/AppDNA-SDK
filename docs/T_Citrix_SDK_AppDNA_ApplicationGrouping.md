# ApplicationGrouping Class
 

A base class to aggregate common functionality for <a href="T_Citrix_SDK_AppDNA_ApplicationGroup">ApplicationGroup</a>.


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;Citrix.SDK.AppDNA.ApplicationGrouping<br />&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_Citrix_SDK_AppDNA_ApplicationGroup">Citrix.SDK.AppDNA.ApplicationGroup</a><br />
**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public abstract class ApplicationGrouping : INotifyPropertyChanged, 
	IEquatable<ApplicationGrouping>
```

###VB
```vbnet
Public MustInherit Class ApplicationGrouping
	Implements INotifyPropertyChanged, IEquatable(Of ApplicationGrouping)
```

The ApplicationGrouping type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationGrouping_Applications">Applications</a></td><td>
Gets the collection of application objects that belong to this grouping.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationGrouping_Description">Description</a></td><td>
Gets a value that is the description of the grouping.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationGrouping_IsDeleted">IsDeleted</a></td><td>
Returns true if the grouping object has been deleted using the SDK.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationGrouping_Name">Name</a></td><td>
Gets a value that is the name of the grouping.</td></tr></table>&nbsp;
<a href="#applicationgrouping-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationGrouping_Add">Add(Application)</a></td><td>
Adds an application to this grouping.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationGrouping_Add_1">Add(IEnumerable(Application))</a></td><td>
Adds application objects to this grouping.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationGrouping_Delete">Delete</a></td><td>
Deletes the ApplicationGrouping object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Equals(Object)</a></td><td>
Determines whether the specified object is equal to the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationGrouping_Equals">Equals(ApplicationGrouping)</a></td><td>
Compares two ApplicationGrouping objects for equality.</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/4k87zsw7" target="_blank">Finalize</a></td><td>
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">GetHashCode</a></td><td>
Serves as a hash function for a particular type.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td>
Gets the <a href="http://msdn2.microsoft.com/en-us/library/42892f65" target="_blank">Type</a> of the current instance.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a" target="_blank">MemberwiseClone</a></td><td>
Creates a shallow copy of the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationGrouping_NotifyPropertyChanged">NotifyPropertyChanged</a></td><td>
Raises the <a href="E_Citrix_SDK_AppDNA_ApplicationGrouping_PropertyChanged">PropertyChanged</a> event.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationGrouping_Remove">Remove(Application)</a></td><td>
Removes an application from this grouping.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationGrouping_Remove_1">Remove(IEnumerable(Application))</a></td><td>
Removes applications from this grouping.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td>
Returns a string that represents the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr></table>&nbsp;
<a href="#applicationgrouping-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_Citrix_SDK_AppDNA_ApplicationGrouping_Deleted">Deleted</a></td><td>
An event that is raised when the grouping is deleted using the SDK.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_Citrix_SDK_AppDNA_ApplicationGrouping_PropertyChanged">PropertyChanged</a></td><td>
Occurs when a property value changes.</td></tr></table>&nbsp;
<a href="#applicationgrouping-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />