# My Superfile Version

- Thanks to [yorukot](https://github.com/yorukot) for the amazing project [superfile](https://github.com/yorukot/superfile).
- [Official Documentation](https://superfile.netlify.app/)

## Description

- This project is the directory with my configuration to superfile (theme, configs, hotkeys).
- The idea is when I use any OS and Terminal I will going to use this version.

## Installation

- Run the following command into any Operational System:

### Linux

```bash

bash -c "$(curl -sLo- https://superfile.netlify.app/install.sh)"

```

### Windows

```bash

powershell -ExecutionPolicy Bypass -Command "Invoke-Expression ((New-Object System.Net.WebClient).DownloadString('https://superfile.netlify.app/install.ps1'))"


```

- To uninstall on windows:

```bash

powershell -ExecutionPolicy Bypass -Command "Invoke-Expression ((New-Object System.Net.WebClient).DownloadString('https://superfile.netlify.app/uninstall.ps1'))"


```

## File Locations

### Windows

- Clone this repository into the `C:\Users\{your-user}\AppData\Local\`.
- Change the name of the repository to `superfile`.
- Run the project with `spf` command.

### Linux

- Clone this repository into the `~/.config/`.
- Change the name of the repository to `superfile`.
- Run the project with `spf` command.

### MacOSX

- TBD

## Keyboard Shortcut

### File Panel Control

| Command | Description |
|---|---|
| `N` | Create a new panel into superfile |
| `Tab` | Go to the next panel created |
| `Shift + Left` | Go to the previous panel created |
| `F` | Toggle file preview panel |
| `O` | Open the sort options menu |
| `R` | Toggle Reverse sort |

### Change the focus panels

| Command | Description |
|---|---|
| `P` | Focus on the Processbar |
| `S` | Focus on Sidebar |
| `M` | Focus on the Metadata |

### Create and Rename Files/Directories

| Command | Description |
|---|---|
| `Ctrl + N` | Create File or Directory |
| `Ctrl + R` | Rename File or Directory |

### File Operations

| Command | Description |
|---|---|
| `Ctrl + C` | Copy Items   |
| `Ctrl + V` | Paste Items  |
| `Ctrl + X` | Cut Items    |
| `Ctrl + D` | Delete Items |

### Edit files


| Command | Description |
|---|---|
| `E` | Open Selected Directory/File into the specified editor |
| `Shift + E` | Open Current Directory into the specified editor |



## Colors

- Base border: `#21262d`
- Border active: `#6c7086`
- Project background color: `#0d1117`
- Project Foreground color: `#cdd6f4`
- Icons and Sidebar tittles: `#56EF19`
- Current folder location: `#FE9900`
- Sidebar selected directory foreground: `#a6e3a1`
- Sidebar selected directory background: `#0d1117`
- Cursor color to move between files/dirs: `#74c7ec`

![Image](images/Color-Scheme.png)
