# Timberborn mod templates
This repository holds all timberborn modding templates from the timberborn modding community

### Installing Timberborn mod templates
TODO: Upload nupkg to nuget

### Development templates  
**Pack templates**  
_*Requires nuget.exe_  
`C:\path\nuget.exe pack`

**Install packed nupkg**  
`dotnet new -i C:\path\Timberborn-Modding-Central.Templates.<<version>>.nupkg`

**Uninstall packed nupkg**  
`dotnet new -u C:\path\Timberborn-Modding-Central.Templates`

### Templates
| Template ID | Shortname  | Description                                                               |
|:-----------|:-----------|:--------------------------------------------------------------------------|
| BasicWithTimberAPI| tmta       | A starting template with TimberAPI, ThunderStorePackage & Automove on build |
