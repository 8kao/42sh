# 42sh

**A minimalist yet powerful Unix shell written in C.**  
This project is part of the Epitech curriculum and aims to recreate a fully functional command-line shell environment.

---

## 🧠 Project Overview

`42sh` is a custom Unix shell that replicates key functionalities of standard shells like `bash` or `zsh`, with internal command handling and external binary execution.  
It supports built-in commands, pipelines, redirections, separators, environment management, and more.

---

## ✨ Features

- ✅ Built-in commands: `cd`, `exit`, `setenv`, `unsetenv`, `env`, `echo`, etc.
- ✅ Execution of external commands (via `execve`)
- ✅ Pipe (`|`) and separator (`;`, `&&`, `||`) support
- ✅ Redirections: `>`, `>>`, `<`, `<<` (heredoc)
- ✅ Environment variable management
- ✅ Command parsing with proper tokenization
- ✅ Return value and error code management
- ✅ Signal handling (e.g., `Ctrl+C`, `Ctrl+D`)
- ✅ Wildcards (`*`) and globbing
- ✅ Clean memory management (checked with Valgrind)
