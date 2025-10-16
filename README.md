# Bai++ Programming Language 🚀

<div align="center">

![Bai++ Logo](https://img.shields.io/badge/Bai++-v1.0-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey?style=for-the-badge)
![Language](https://img.shields.io/badge/Language-Bisaya-orange?style=for-the-badge)

**Program sa Bisaya, Para sa Bisaya!** 🇵🇭

*A simple, Bisaya-based programming language for learning and calculations*

[Download Latest Release](https://github.com/YOUR_USERNAME/bai-plus-plus/releases/latest) • [View Samples](#sample-programs) • [Documentation](#documentation)

</div>

---

## 📖 About Bai++

**Bai++** is a beginner-friendly programming language that uses **Bisaya keywords** to make coding more accessible and fun for Bisaya speakers. Whether you're a student learning programming basics or just want to build simple calculators, Bai++ makes it easy!

### ✨ Why Bai++?

- 🌍 **Learn in your native language** - No need to struggle with English programming terms
- 🎓 **Perfect for beginners** - Simple syntax, easy to understand
- 💻 **No installation hassles** - Download and run immediately
- 🆓 **Completely free** - Open source and available to everyone
- 🎨 **Built-in IDE** - Code editor with syntax highlighting included

---

## 🎯 Features

- ✅ **Bisaya Syntax** - Use familiar Bisaya words to program
- ✅ **Variable Assignment** - Store and manipulate values
- ✅ **Arithmetic Operations** - Add, subtract, multiply, divide
- ✅ **Syntax Highlighting** - Color-coded keywords for easy reading
- ✅ **Save/Load Programs** - Work with `.bai` files
- ✅ **Error Messages in Bisaya** - Understand what went wrong
- ✅ **Standalone Executable** - No Python or dependencies needed
- ✅ **Sample Programs** - 8 ready-to-run examples included

---

## 📥 Quick Start

### Option 1: Download Executable (Recommended)

**For Users (No Programming Experience Needed):**

1. Go to [Releases](https://github.com/YOUR_USERNAME/bai-plus-plus/releases/latest)
2. Download `BaiPlusPlus.exe`
3. Download `sample_programs.zip` (optional but recommended)
4. Double-click `BaiPlusPlus.exe` to start coding!

> **Note:** Windows might show a security warning. Click "More info" → "Run anyway"

### Option 2: Run from Source

**For Developers:**

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/bai-plus-plus.git
cd bai-plus-plus

# Run the IDE
python bai_ide.py
```

**Requirements:** Python 3.7 or higher

---

## 🎓 Language Syntax

### Keywords Reference

| Bisaya Keyword | English | Description | Example |
|----------------|---------|-------------|---------|
| `ibutang` | assign | Assign a value to variable | `ibutang x = 10` |
| `ipakita` | show/display | Display output | `ipakita x` |
| `idugang` | add | Addition operation | `idugang x ug y` |
| `ikuha` | subtract | Subtraction operation | `ikuha x ug y` |
| `ipilo` | multiply | Multiplication operation | `ipilo x ug y` |
| `ibahin` | divide | Division operation | `ibahin x ug y` |
| `ug` | and/with | Connects operands | `x ug y` |
| `//` | comment | Add comments | `// This is a comment` |

### Basic Example

```bai
// My First Bai++ Program
ibutang x = 50
ibutang y = 10

// Perform calculations
ipakita idugang x ug y    // Output: 60
ipakita ikuha x ug y      // Output: 40
ipakita ipilo x ug y      // Output: 500
ipakita ibahin x ug y     // Output: 5
```

---

## 📝 Sample Programs

### 1. Simple Calculator
```bai
// Basic Calculator
ibutang num1 = 100
ibutang num2 = 25

ipakita idugang num1 ug num2    // 125
ipakita ikuha num1 ug num2      // 75
ipakita ipilo num1 ug num2      // 2500
ipakita ibahin num1 ug num2     // 4
```

### 2. Shopping Total
```bai
// Calculate shopping expenses
ibutang sapatos = 1500
ibutang baju = 800
ibutang bag = 1200

ibutang total = idugang sapatos ug baju
ibutang final = idugang total ug bag
ipakita final    // Output: 3500
```

### 3. Grade Calculator
```bai
// Calculate average grade
ibutang quiz1 = 85
ibutang quiz2 = 90
ibutang quiz3 = 88

ibutang total = idugang quiz1 ug quiz2
ibutang sum = idugang total ug quiz3
ibutang average = ibahin sum ug 3
ipakita average    // Output: 87.67
```

**[View More Examples →](sample_programs/)**

---

## 🖥️ IDE Features

The Bai++ IDE comes with everything you need:

- **Code Editor** - Write your Bai++ programs
- **Syntax Highlighting** - Keywords are color-coded
- **Run Button** - Execute your code instantly (F5)
- **Output Panel** - See your results
- **File Operations** - New, Open, Save, Save As
- **Help Menu** - Built-in syntax guide
- **Dark Theme** - Easy on the eyes

### Keyboard Shortcuts

- `F5` - Run program
- `Ctrl+N` - New file
- `Ctrl+O` - Open file
- `Ctrl+S` - Save file

---

## 🛠️ Building from Source

Want to build the executable yourself?

```bash
# Install PyInstaller
pip install pyinstaller

# Build the executable
python build_exe.py

# Find your executable in dist/
# Output: dist/BaiPlusPlus.exe
```

Or use the quick start script:
```bash
# On Windows
quick_start.bat
# Choose option 3: Build Executable
```

---

## 📚 Documentation

### File Extensions
- `.bai` - Bai++ source code files

### Variable Naming
- Use letters and numbers
- Cannot start with a number
- Case-sensitive (`x` and `X` are different)

### Numbers
- Integer: `10`, `100`, `5000`
- Decimal: `10.5`, `3.14`, `99.99`

### Comments
```bai
// Single line comment
// Comments are ignored when running
```

### Error Handling
Bai++ provides helpful error messages:
```
ERROR sa line 3: Variable 'x' dili pa gi-define (not defined)
ERROR sa line 5: Dili pwede mag-divide by zero! (Cannot divide by zero!)
```

---

## 🎯 Use Cases

Perfect for:
- 📚 Learning programming basics
- 🧮 Building simple calculators
- 💰 Budget calculations
- 📊 Grade computations
- 🏪 Shopping totals
- 📐 Mathematical formulas
- 🎓 Teaching programming to Bisaya speakers

---

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. **Report Bugs** - Found an issue? [Open an issue](https://github.com/YOUR_USERNAME/bai-plus-plus/issues)
2. **Suggest Features** - Have an idea? We'd love to hear it!
3. **Submit Pull Requests** - Improve the code
4. **Create Sample Programs** - Share your Bai++ creations
5. **Improve Documentation** - Help others learn

See [CONTRIBUTING.md](CONTRIBUTING.md) for details.

### Ideas for Contributions
- Add more Bisaya keywords
- Implement loops (`para`, `samtang`)
- Add conditional statements (`kon`, `kondili`)
- Create more sample programs
- Improve error messages
- Add string support
- Build macOS/Linux versions

---

## 📋 Roadmap

### Version 1.0 ✅ (Current)
- [x] Basic arithmetic operations
- [x] Variable assignment
- [x] IDE with syntax highlighting
- [x] Save/Load .bai files
- [x] Standalone executable

### Version 1.1 🔄 (Planned)
- [ ] Conditional statements (`kon`, `kondili`)
- [ ] Loops (`para`, `samtang`)
- [ ] String support
- [ ] Better error messages
- [ ] More sample programs

### Version 2.0 🔮 (Future)
- [ ] Functions/procedures
- [ ] Arrays/lists
- [ ] File operations
- [ ] Advanced math operations
- [ ] Debugging tools

---

## 📊 System Requirements

### For Users (Executable)
- **OS:** Windows 7 or higher
- **RAM:** 100 MB
- **Storage:** 50 MB free space
- **No Python required!**

### For Developers (Source)
- **Python:** 3.7 or higher
- **OS:** Windows, macOS, Linux
- **Dependencies:** tkinter (usually included with Python)

---

## 🐛 Troubleshooting

### "Windows protected your PC" warning
This is normal for unsigned executables.
- Click **"More info"**
- Click **"Run anyway"**

### Cannot open .bai files
- Make sure file extension is `.bai` not `.bai.txt`
- Save files with proper encoding (UTF-8)

### Executable won't run
- Run as Administrator
- Check if antivirus is blocking it
- Make sure you're on Windows

[More troubleshooting →](https://github.com/YOUR_USERNAME/bai-plus-plus/wiki/Troubleshooting)

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

**TL;DR:** You can use, modify, and distribute this freely!

---

## 👨‍💻 Author

Created with ❤️ by **[Your Name]**

- GitHub: [@YOUR_USERNAME](https://github.com/YOUR_USERNAME)
- Email: your.email@example.com (optional)

---

## 🙏 Acknowledgments

- Thanks to the Bisaya community for inspiration
- Special thanks to all contributors
- Built with Python and tkinter

---

## 📞 Support

Need help? Have questions?

- 📖 [Read the Documentation](#documentation)
- 🐛 [Report a Bug](https://github.com/YOUR_USERNAME/bai-plus-plus/issues)
- 💡 [Request a Feature](https://github.com/YOUR_USERNAME/bai-plus-plus/issues)
- 💬 [Discussions](https://github.com/YOUR_USERNAME/bai-plus-plus/discussions)

---

## ⭐ Show Your Support

If you find Bai++ helpful, please consider:
- ⭐ Starring this repository
- 🐛 Reporting bugs
- 📢 Sharing with friends
- 🤝 Contributing code

---

## 📈 Statistics

![GitHub stars](https://img.shields.io/github/stars/YOUR_USERNAME/bai-plus-plus?style=social)
![GitHub forks](https://img.shields.io/github/forks/YOUR_USERNAME/bai-plus-plus?style=social)
![GitHub issues](https://img.shields.io/github/issues/YOUR_USERNAME/bai-plus-plus)
![GitHub downloads](https://img.shields.io/github/downloads/YOUR_USERNAME/bai-plus-plus/total)

---

<div align="center">

**Maayong pagsulay!** (Good luck!)

**Bai++ - Programming in Bisaya, Made Simple** 🇵🇭

[⬆ Back to Top](#bai-programming-language-)

</div>

---

## 🔗 Links

- **Website:** [Coming Soon]
- **Documentation:** [Wiki](https://github.com/YOUR_USERNAME/bai-plus-plus/wiki)
- **Releases:** [Download Here](https://github.com/YOUR_USERNAME/bai-plus-plus/releases)
- **Issues:** [Report Bugs](https://github.com/YOUR_USERNAME/bai-plus-plus/issues)
- **Discussions:** [Join the Community](https://github.com/YOUR_USERNAME/bai-plus-plus/discussions)

---

*Made with 💙 for the Bisaya programming community*

*"Ang programming dili na lisud, kay Bisaya na siya!" (Programming is no longer difficult, because it's in Bisaya!)*
