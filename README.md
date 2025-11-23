# 📘 2.1 Command Line Basics (Weight: 3)
**Basics of using the Linux command line.**

---

## 📝 **Key Knowledge Areas — Study Notes**

### ⭐ **Basic Shell**
- The shell is the **command-line interpreter** 🖥️  
- Common shell: **Bash** (Bourne Again Shell)  
- Interprets commands, scripts, and environment variables  
- Supports **interactive use** and **scripting**

---

### ⭐ **Command Line Syntax**
- Commands follow structure: `command [options] [arguments]`  
- Options/flags modify behavior (`ls -l`, `cp -r`)  
- Commands are **case-sensitive**  
- Chain commands with `;` or pipes `|`  
- Redirect output: `>` (overwrite), `>>` (append)

---

### ⭐ **Variables**
- Store **data for shell sessions** 🌐  
- Example: `MYVAR="Hello"` → access with `$MYVAR`  
- Environment variables affect system behavior, e.g., **PATH**  
- Temporary vs exported variables:
  - Local: `MYVAR="value"`  
  - Exported: `export MYVAR="value"` → available to child processes

---

### ⭐ **Quoting**
- Controls **how shell interprets text**  
- **Single quotes `' '`** → literal, no expansion  
- **Double quotes `" "`** → allows variable and command expansion  
- **Backticks `` ` ` `` or $( )** → command substitution

---

### 🧩 **Partial List of Key Knowledge — Notes & Context**
- **Bash** → Default Linux shell, supports scripting & interactive commands  
- **echo** → Print text or variables to terminal (`echo "Hello"`, `echo $PATH`)  
- **history** → Shows previously executed commands, useful for review  
- **PATH environment variable** → Directories shell searches for commands  
- **export** → Make variable available to child processes  
- **type** → Show how a command will be interpreted (`type ls`, `type echo`)  

---

### ⚡ **Practice Tips**
- Open terminal and check shell: `echo $SHELL`  
- Display environment variables: `echo $PATH`  
- Print text or variables: `echo "Hello World"` or `echo $HOME`  
- Review command history: `history | tail`  
- Experiment with variables and quoting:  
  - `MYVAR="Test"` → `echo $MYVAR`  
  - `echo 'Literal $MYVAR'` vs `echo "Expanded $MYVAR"`  
- Use `type` to inspect commands: `type ls`, `type echo`  
