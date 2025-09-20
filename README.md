# Windows-rEFInd-Theme-Manager
[![made-with-powershell](https://img.shields.io/badge/PowerShell-1f425f?logo=Powershell)](https://microsoft.com/PowerShell)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Discord](https://img.shields.io/discord/1419019684073832470)

PowerShell scripts to back up and restore Windows themes for rEFInd, keeping your customizations safe and easy to manage.

---

## 🌟 Features

- **Backup any theme folder** with a timestamp
- **Restore themes** to their original location effortlessly
- **Customizable paths** – works with any theme folder you choose
- **Clear naming** – restored themes are easy to identify
- Lightweight PowerShell scripts, no installation required

---

## ⚙️ Setup

Before running the scripts, create the following folders. You can do this via Command Prompt (replace [your-name] with your Windows username):

```powershell
# Windows-rEFInd-Theme-Manager
[![made-with-powershell](https://img.shields.io/badge/PowerShell-1f425f?logo=Powershell)](https://microsoft.com/PowerShell)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

PowerShell scripts to back up and restore Windows themes for rEFInd, keeping your customizations safe and easy to manage.

---

## 🌟 Features

- **Backup any theme folder** with a timestamp
- **Restore themes** to their original location effortlessly
- **Customizable paths** – works with any theme folder you choose
- **Clear naming** – restored themes are easy to identify
- Lightweight PowerShell scripts, no installation required

---

## ⚙️ Setup

Before running the scripts, create the following folders. You can do this via Command Prompt (replace [your-name] with your Windows username):

```powershell
# Windows-rEFInd-Theme-Manager
[![made-with-powershell](https://img.shields.io/badge/PowerShell-1f425f?logo=Powershell)](https://microsoft.com/PowerShell)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

PowerShell scripts to back up and restore Windows themes for rEFInd, keeping your customizations safe and easy to manage.

---

## 🌟 Features

- **Backup any theme folder** with a timestamp
- **Restore themes** to their original location effortlessly
- **Customizable paths** – works with any theme folder you choose
- **Clear naming** – restored themes are easy to identify
- Lightweight PowerShell scripts, no installation required

---

## ⚙️ Setup

Before running the scripts, create the following folders. You can do this via Command Prompt (replace [your-name] with your Windows username):

```powershell
mkdir "C:\Users\[your-name]\Documents\refined themes"
mkdir "C:\Users\[your-name]\Documents\refined themes - backup"
```

Replace [your-name] with your Windows username. These folders will store your themes and backups.

## Usage

### Back Up a Theme
Run the backup script from PowerShell in the project folder:

```powershell
.\Backup-Theme.ps1
```

The script will prompt you for:

- The path to the theme folder.
- The name of the theme.

Your theme will be safely copied to:

```text
C:\Users\[your-name]\Documents\refined themes - backup
```

### Restore a Theme
To restore a previously backed-up theme, run the restore script (replace [ThemeName]):

```powershell
.\Restore-Theme-[ThemeName].ps1
```

Replace [ThemeName] with the name of the theme you want to restore.

The script will copy the theme back to:

```text
C:\Users\[your-name]\Documents\refined themes
```

## Why This Script

Quickly switch between themes for rEFInd without losing work.

Avoid accidental theme deletion or overwrites.

Keep backups organized and accessible.

## File Structure

```text
refined themes
│   └── YourThemeFolder
refined themes - backup
│   └── YourThemeFolder_Backup
Backup-Theme.ps1
Restore-Theme-[ThemeName].ps1
README.md
```

## Contributing

Contributions are welcome!

Feel free to:

- Suggest improvements.
- Add new features or automation.
- Submit bug reports.

## License

This project is MIT licensed.

MIT License

Script generated with the help of ChatGPT. Credit where due.

## Thank You

If you find this tool useful, consider ⭐ starring the repo.
Feedback and feature requests are always appreciated!
Avoid accidental theme deletion or overwrites.
