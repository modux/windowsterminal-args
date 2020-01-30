# Windows Terminal Args

Windows Terminal profile to enable command line arguments.

Pass your command line parameters through wt.exe and onto powershell, cmd or wsl

Works with Powershell.exe, cmd.exe, wsl.exe and more (Windows Subsystem for Linux)  

The current working directory is also passed through to the new shell 

## Usage
Just load regular cmd
```
wt
```

Load regular cmd with command
```
wt cmd /c whoami
```

Load PowerShell
```
wt powershell
```

Run a command 
```
wt ipconfig
```

Load Windoews Subsystem Linux (wsl) 
```
wt wsl
```
### Installing

Download the profiles.json and replace it with your current profile. (wt.exe => Arrow Menu => Settings => Copy and paste replace)

### Prerequisites

Microsoft Windows Terminal
https://github.com/microsoft/terminal

## Built With

PowerShell

## Authors

* **Sash Rigby @ Modux ** -  - [secdefect](https://twitter.com/secdefect)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.
