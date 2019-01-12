# GetAPLProjectPath

Returns the path all Dyalog APL (acre) projects are stored under. 

For that the Registry key `HKCU\Software\APLTree\AplProjectPath` is read.

If the value is not yet defined the user command allows you to define it.

Notes:

* This is a Windows-only user command.
* The value is stored deliberately under HKCU (current user) rather than HKLM (local machine) because that allows different users to have different folders.


