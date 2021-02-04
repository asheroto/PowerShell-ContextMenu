
# Add/Remove PowerShell from Context Menu

**This script enables you to add or remove PowerShell or PowerShell Core to the context menu of any directory:**

![ListValues pamemoryeter](https://raw.githubusercontent.com/asheroto/PowerShell-in-Context-Menu/main/screenshots/ContextMenu.png)

**PowerShell is evolving.**  PowerShell.exe's latest version is 5.1, whereas PowerShell Core, the next generation of PowerShell, is version 7.1.  If you haven't upgraded to **PowerShell Core** / PowerShell 7, [check it out](https://github.com/powershell/powershell).

|Parameter|Description|
|--|--|
|-Add|Adds PowerShell to the context menu|
|-AddPowerShellCore|Adds PowerShell Core to the context menu|
|-Remove|Removes PowerShell from the context menu|
|-RemovePowerShellCore|Removes PowerShell Core from the context menu|

**You need to log off and log in for changes to take effect.  Alternatively you can restart your computer.**

## Example Usage

**Adds PowerShell to the Context Menu:**

`.\PowerShell-ContextMenu.ps1 -Add`

**Adds PowerShell Core to the Context Menu:**

`.\PowerShell-ContextMenu.ps1 -AddPowerShellCore`

**Remove PowerShell to the Context Menu:**

`.\PowerShell-ContextMenu.ps1 -Remove`

**Remove  PowerShell Core to the Context Menu:**

`.\PowerShell-ContextMenu.ps1 -RemovePowerShellCore`
