#Import applications
Before an application can be analyzed, it must be imported into AppDNA. Two types of import are available using the SDK: direct import and install capture.



using AppDNA = Citrix.SDK.AppDNA;
AppDNA.Server appdna;








public Dictionary<string,AppDNA.Application> Import(IEnumerable<string> msiSourceFiles)













public Dictionary<string, AppDNA.Application> InstallCapture(IEnumerable<string> legacySetupFiles)












