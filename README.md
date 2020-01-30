# windowsterminal-args

Windows Terminal Profile to enable command line arguments

## Getting Started

Works with Powershell.exe, cmd.exe, wsl.exe and more (Windows Subsystem for Linux)  

The current working directory is also passed through to the new shell 

### Prerequisites

Microsoft Windows Terminal
https://github.com/microsoft/terminal


### Installing

Download the profiles.json and replace it with your current profile. (wt.exe => Arrow Menu => Settings => Copy and paste replace)


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

## Built With

PowerShell

## Authors

* **Sash Rigby @ Modux ** -  - [secdefect](https://twitter.com/secdefect)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.
