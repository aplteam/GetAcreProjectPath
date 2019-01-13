# GetAPLProjectPath

Returns the path all your Dyalog APL (acre) projects are stored under. 

For that the Registry key `HKCU\Software\APLTree\AcreProjectPath` is read.

If the value is not yet defined the user command allows you to define it.

Notes:

* For the time being this is a Windows-only user command.
* This is not a general user command. You might need this only when you manage projects with [acre](https://github.com/carlislegroup/acre-desktop). 

  Note that some utilities that help manage acre projects like [Maker](https://gitHub.com/aplteam/Maker) rely on this user command being available.
* The value is stored deliberately under HKCU (current user) rather than HKLM (local machine) because that allows different users to have different folders.


