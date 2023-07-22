# Fallout: New Vegas Script Syntax

This extension provides a TextMate grammar for the scripting language used in The Fallout: New Vegas (fnvscript). to use with [Hot Reload (NVSE)](https://www.nexusmods.com/newvegas/mods/70962).

This is a fork from tes4_vscode_syntax, right now it's only an adaptation for the extension .gek

![](https://raw.githubusercontent.com/W0lfwang/FNV_vscode_syntax/main/images/example.png)

## Features

This extension highlights the following:

* Variable types
* Script blocks
* Conditional blocks
* String format specifiers
* Comments
* Numbers
* Player and PlayerRef

It also highlights 364 Construction Set functions, and 1467 OBSE functions (FNV functions should be added). These were generated from the [raw function list](https://cs.elderscrolls.com/index.php?title=Raw_Function_List) on the Construction Set wiki.

Intended to work with [Hot Reload (NVSE)](https://www.nexusmods.com/newvegas/mods/70962) and it's **Compile scripts on file save** function.

## Known Issues

Just starting. Please let me know of any issues on [Github](https://github.com/W0lfwang/FNV_vscode_syntax).

## Compiling

### 1. Install Node.js and npm:
Make sure you  have Node.js (which includes npm - Node Package Manager) installed on your computer. You can download the latest version from the official [Node.js website](https://nodejs.org/). 

### 2. Pack the Extension:
To package your extension into a .vsix file, you can use the vsce tool. If you haven't installed it yet, you can do so by running:
```
npm install -g vsce
```

Once vsce is installed, navigate to the root directory of your extension and run:
```
vsce package
```
### 3. Install the Extension in Visual Studio Code:
Open Visual Studio Code, go to the Extensions view (Ctrl+Shift+X or Cmd+Shift+X), click on the "More actions" menu (three dots), choose "Install from VSIX," and select the .vsix file you generated in the previous step.