# Unity IDE Extensions

Essential Visual Studio Code extensions for Unity development with C# support, debugging, and Unity-specific tooling.

## What's Included

- **C# Dev Kit** - Comprehensive C# development tools
- **C#** - Language support with IntelliSense and debugging
- **Visual Studio Tools for Unity** - Unity debugging and project support
- **.NET Install Tool** - Automatic .NET runtime management

## Prerequisites

- **Visual Studio Code** - Download from https://code.visualstudio.com/
- **Unity Editor** (recommended)

## Installation

1. **Download** the `.vsix` files from this repository

2. **Install Extensions**:
   - Open Visual Studio Code
   - Press `F1` or `Ctrl+Shift+P` (`Cmd+Shift+P` on macOS) to open Command Palette
   - Type `Extensions: Install from VSIX...` and select it
   - Browse and select each `.vsix` file to install:
     - `ms-dotnettools.vscode-dotnet-runtime-2.3.7.vsix`
     - `ms-dotnettools.csharp-1.23.16.vsix`
     - `ms-dotnettools.csdevkit-1.30.44-win32-x64.vsix`
     - `visualstudiotoolsforunity.vstuc-1.1.2.vsix`

3. **Restart** Visual Studio Code to complete installation

## Verification

1. Open Extensions view (`Ctrl+Shift+X` / `Cmd+Shift+X`)
2. Check that all four extensions appear as **"Enabled"** in the installed section
3. Open a Unity project to test C# IntelliSense and debugging features

## Troubleshooting

**Extensions not working?**
- Restart VS Code completely
- Reload window: `F1` → "Developer: Reload Window"
- Check Output panel for error messages

**Unity integration issues?**
- Set VS Code as external script editor in Unity: **Edit** → **Preferences** → **External Tools**

---

Open any Unity project folder in VS Code to start developing with enhanced C# support and debugging capabilities.
