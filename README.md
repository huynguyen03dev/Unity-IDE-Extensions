# Unity IDE Extensions

A collection of essential Visual Studio Code extensions for Unity development, providing enhanced C# support, debugging capabilities, and Unity-specific tooling.

## Extensions Included

This package includes the following extensions:

- **C# Dev Kit** (`ms-dotnettools.csdevkit`) - Comprehensive C# development tools
- **C#** (`ms-dotnettools.csharp`) - C# language support with IntelliSense and debugging
- **Visual Studio Tools for Unity** (`visualstudiotoolsforunity.vstuc`) - Unity-specific debugging and project support
- **.NET Install Tool** (`ms-dotnettools.vscode-dotnet-runtime`) - .NET runtime management

## Prerequisites

- **Visual Studio Code** must be installed on your system
  - Download from: https://code.visualstudio.com/
- **Unity Editor** (recommended for full functionality)
- **.NET SDK** (will be managed automatically by the .NET Install Tool extension)

## Installation

### Option 1: Install from VSIX Files (Recommended)

1. **Download the Extensions**
   - Clone this repository or download the `.vsix` files directly
   - Ensure you have all four `.vsix` files in your local directory

2. **Install Extensions in Visual Studio Code**
   
   a. Open **Visual Studio Code**
   
   b. Navigate to the **Extensions view**:
      - **Windows/Linux**: Press `Ctrl+Shift+X`
      - **macOS**: Press `Cmd+Shift+X`
   
   c. Access the Extensions menu:
      - Click the **three-dot menu** (`...`) in the Extensions view header
      - Select **"Install from VSIX..."** from the dropdown menu
   
   d. Install each extension:
      - Browse and select the first `.vsix` file
      - Click **"Install"**
      - Repeat for all four `.vsix` files:
        - `ms-dotnettools.vscode-dotnet-runtime-2.3.7.vsix`
        - `ms-dotnettools.csharp-1.23.16.vsix`
        - `ms-dotnettools.csdevkit-1.30.44-win32-x64.vsix`
        - `visualstudiotoolsforunity.vstuc-1.1.2.vsix`

3. **Complete Installation**
   - **Restart Visual Studio Code** to ensure all extensions are properly loaded
   - Allow any additional dependencies to install automatically

### Option 2: Build from Source

If you prefer to build the extensions yourself:

1. Clone the repository
2. Follow the build instructions for each extension
3. Install the generated `.vsix` files using the steps above

## Verification

To verify the extensions are properly installed:

1. Open Visual Studio Code
2. Navigate to **Extensions** (`Ctrl+Shift+X` / `Cmd+Shift+X`)
3. Search for each extension by name or check the **"Installed"** section
4. Ensure all four extensions show as **"Enabled"**:
   - ✅ C# Dev Kit
   - ✅ C#
   - ✅ Visual Studio Tools for Unity
   - ✅ .NET Install Tool

5. **Test Unity Integration**:
   - Open a Unity project in VS Code
   - Verify IntelliSense works in C# scripts
   - Check that Unity-specific features are available

## Troubleshooting

### Common Issues

**Extensions not appearing after installation:**
- Restart Visual Studio Code completely
- Check if Windows Defender or antivirus software blocked the installation
- Ensure you have sufficient permissions to install extensions

**C# IntelliSense not working:**
- Verify the .NET SDK is installed (the .NET Install Tool should handle this)
- Reload the VS Code window: `Ctrl+Shift+P` → "Developer: Reload Window"
- Check the Output panel for any error messages

**Unity debugging not working:**
- Ensure Unity Editor is set to use Visual Studio Code as the external script editor
- In Unity: **Edit** → **Preferences** → **External Tools** → **External Script Editor**
- Select the VS Code executable path

**Permission errors during installation:**
- Run Visual Studio Code as administrator (Windows) or with appropriate permissions
- Check that the `.vsix` files are not corrupted or blocked

### Getting Help

If you encounter issues:

1. Check the **Output** panel in VS Code for error messages
2. Review the **Problems** panel for any workspace issues
3. Consult the official documentation for each extension
4. Ensure your Unity project is properly configured for external script editing

## Usage

Once installed, these extensions will automatically:

- Provide C# syntax highlighting and IntelliSense
- Enable debugging for Unity projects
- Offer code completion and error detection
- Support Unity-specific workflows and project structures

Open any Unity project folder in VS Code to start using the enhanced development environment.

---

**Note**: These extensions are specifically configured for Unity development. For general C# development outside of Unity, you may want to consider additional or alternative extensions.
