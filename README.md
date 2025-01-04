# Setting Up Custom Scripts on Windows

Follow these steps to add your custom scripts directory to your system's PATH for easy execution from anywhere.

---

## 1. Locate Your Profile Configuration File

On Windows, this is usually one of the following files, depending on your environment:

- `.profile`
- `.bash_profile`

You can find this file in your `$HOME` directory which is this:  
`C:/Users/(Your User Name)/`

## 2. Open the Profile Configuration File

Use a text editor of your choice (e.g., Notepad or VS Code) to open the appropriate file.

## 3. Add the Custom Scripts Directory to PATH

Append the following line to the file:

```bash
export PATH=$HOME/custom-scripts:$PATH
```
---
