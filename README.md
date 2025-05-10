# Snippets README

Welcome to your custom VS Code snippets! This file serves as a guide to help you manage and organize your snippets effectively.

## 📂 File Location

This file is located at:
```
/home/{Username}/.config/Code/User/snippets/README.md
```

## ✨ What Are Snippets?

Snippets are reusable pieces of code that can be quickly inserted into your files. They help you save time and maintain consistency in your coding workflow.

## 📖 How to Use Snippets

1. Open the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P`).
2. Search for `Preferences: Configure User Snippets`.
3. Select the language or global snippets file.
4. Add or edit your snippets in JSON format.

## 🛠️ Snippet Structure

Each snippet follows this structure:
```json
"Snippet Name": {
    "prefix": "shortcut",
    "body": [
        "Your snippet code here"
    ],
    "description": "A brief description of the snippet"
}
```

## 🌟 Example Snippet

```json
"Print to Console": {
    "prefix": "log",
    "body": [
        "console.log('$1');"
    ],
    "description": "Logs output to the console"
}
```

## 📋 Tips

- Use `$1`, `$2`, etc., for tab stops.
- Use `\\` to escape special characters.
- Test your snippets to ensure they work as expected.

## 📚 Resources

- [VS Code Snippets Documentation](https://code.visualstudio.com/docs/editor/userdefinedsnippets)

Happy coding! 🚀