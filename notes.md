# Notes

# IIS

To use IIS drive: `IIS:\`

`Import-Module WebAdministration`

Get Application Pool Properties

`Get-ItemProperty IIS:\AppPools\MyAppPool | select *`

Set Application Pool runtime version

`Set-ItemProperty -Path IIS:\AppPools\MyAppPool -Name managedRuntimeVersion -Value 'v4.0'`

# SQL Server



