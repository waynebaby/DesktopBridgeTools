# Usage
`MakeAPPXForWindows10S.cmd "C:\Temp\MyDesktopBridgeFile.appx"`

# Actions
1. Creates a new unique folder for extracting the APPX files
2. Modifies the 'CN' in the extracted AppxManifest.xml
3. Recreates the Appx file with the modified AppxManifest.xml
4. Signs the Appx file with the AppxTestRootAgency provided by the Store team
