# PSWinEventSubscriptions
Module and Scripts for working with the Windows Event Collector (poor man's SIEM)
This was written to easily interact with wecutil.exe

# Installation
To "install" this module, create a folder named "EventSubscriptions" in any of your $Env:PSModulePath folders, and place EventSubscriptions.psm1 inside.

# Usage
Import-Module EventSubscriptions

Get-Command -Module EventSubscriptions

Get-Help Get-WECSubscription -Examples

Get-Help Set-WECSubscription -Examples