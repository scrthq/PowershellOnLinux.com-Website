### Favorite Modules

- Below you will find a list of **PowerShell Modules** that we've found useful.
- The modules were tested on Linux and verified to work.
--- 
#### UniversalDashboard.Community
##### Note
The PowerShellOnLinux.com website is built on this modules.

##### Description
PowerShell Universal Dashboard is a web framework for PowerShell developers. Create websites, REST APIs and dashboards with only PowerShell script. The client and server side code for the dashboard is authored completely in PowerShell. Charts, monitors, tables and grids can easily be created with the cmdlets included with the module.The module is cross-platform and will run anywhere Windows PowerShell or PowerShell Core can run.  
[Website](https://universaldashboard.io/), [GitHub](https://github.com/ironmansoftware/universal-dashboard),  [Get Started](https://docs.universaldashboard.io/getting-started)

##### Install

```
Install-Module UniversalDashboard.Community -AcceptLicense
```

--- 
#### Selenium PowerShell

##### Description
Selenium automates browsers. That's it! What you do with that power is entirely up to you. Primarily, it is for automating web applications for testing purposes, but is certainly not limited to just that. Boring web-based administration tasks can (and should!) be automated as well. This module is a powershell implementation of Selenium.  
[Github](https://github.com/adamdriscoll/selenium-powershell)

##### Install

```
Install-Module Selenium
```
---
#### dbatools

##### Description
If you want to manage MS SQL servers from Linux this is the module for you!.  
At the time of this writing the module is only 75% compatible with Linux but hopefully it wont be long until we see 100% compatibility.

dbatools is a free PowerShell module with over 500 SQL Server administration, best practice and migration commands included.

[Website](https://dbatools.io/), [GitHub](https://github.com/sqlcollaborative/dbatools), [Get Started](https://dbatools.io/getting-started/)

##### Install

```
Install-Module dbatools
```

---
#### VMware PowerCLI
##### Description
VMware describes PowerCLI as a powerful command-line tool that lets you automate all aspects of vSphere management, including network, storage, VM, guest OS and more. 
The PowerCLI Module includes over 500 PowerShell cmdlets for managing and automating vSphere.

PowerCLI runs in PowerShell on Linux, macOS and Windows operating systems.  

##### Install

```
Install-Module VMware.PowerCLI
```

---
#### FreeNas

##### Description
If you want to manage FreeNAS/TrueNAS servers from PowerShell on Linux/Mac/Windows this is the module for you.  
This module uses the FreeNas and TrueNas Rest v1.0 API.   
You can find more information in this [Blog Post](https://jm2k69.github.io/2019-03-18-PowerShell-Module-for-FreeNas-and-TrueNas/)

[GitHub](https://github.com/JM2K69/FreeNas)

##### Install

```
Install-Module FreeNAS
```

---
#### Posh-Git

##### Description
Posh-Git is a PowerShell module that integrates Git and PowerShell by providing Git status summary information that can be displayed in the PowerShell prompt, e.g.:  
<img src='https://raw.githubusercontent.com/wiki/dahlbyk/posh-git/images/PromptDefaultLong.png'>  
posh-git also provides tab completion support for common git commands, branch names, paths and more.
For example, with posh-git, PowerShell can tab complete git commands like `checkout` by typing `git ch` and pressing
the <kbd>tab</kbd> key. That will tab complete to `git checkout` and if you keep pressing <kbd>tab</kbd>, it will
cycle through other command matches such as `cherry` and `cherry-pick`. You can also tab complete remote names and
branch names e.g.: `git pull or<tab> ma<tab>` tab completes to `git pull origin master`.

[Website](http://dahlbyk.github.io/posh-git/), [GitHub](https://github.com/dahlbyk/posh-git)

##### Install

```
Install-Module Posh-Git
```

---
#### PSGSuite

##### Description
PSGSuite is a module wrapping Google's .NET SDKs to enable automation of G Suite admin operations, including Gmail and Drive interaction.
It is designed to work anywhere PowerShell runs and includes automated CI testing pre-deployment on Ubuntu images, both for the current stable release of PowerShell Core as well as the latest PowerShell Preview release via custom Docker container running Ubuntu 18.04. 
PSGSuite also works with free Gmail and non-admin G Suite accounts for easy Gmail, Drive and Calendar interaction without the need for a full G Suite admin account to use.

[Website & Documentation](https://psgsuite.io/), [GitHub](https://github.com/scrthq/PSGSuite)

##### Install

```
Install-Module PSGSuite
```

---
#### VaporShell

##### Description
VaporShell is a module that abstracts AWS CloudFormation template building in JSON/YAML into full, dynamic PowerShell code. It features input type validation to ensure that the resources you add to your template are correct before deploying, as well as full CloudFormation stack management by leveraging AWS' .NET SDK underneath the hood.
It is designed to work anywhere PowerShell runs and includes automated CI testing pre-deployment on Ubuntu images, both for the current stable release of PowerShell Core as well as the latest PowerShell Preview release via custom Docker container running Ubuntu 18.04.

[Website & Documentation](https://vaporshell.io/), [GitHub](https://github.com/scrthq/VaporShell)

##### Install

```
Install-Module VaporShell
```

---
#### PSProfile

##### Description
PSProfile is a module designed for PowerShell profile management, which includes a lot of features focused around increasing productivity from your console. It includes features to easily tab-complete common Git project folders on your machine, manage various PowerShell prompts, as well as provide handy quality-of-life improvements while working in a PowerShell console.
It is designed to work anywhere PowerShell runs and includes automated CI testing pre-deployment on Ubuntu images, both for the current stable release of PowerShell Core as well as the latest PowerShell Preview release via custom Docker container running Ubuntu 18.04.

[Documentation](https://github.com/scrthq/PSProfile/wiki), [GitHub](https://github.com/scrthq/PSProfile)

##### Install

```
Install-Module PSProfile
```
