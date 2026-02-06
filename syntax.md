# 🛠️ Gemini CLI Master Command List

### 🚀 Core Management Commands

* **/help** – Displays all available commands and keyboard shortcuts.
* **/settings** – Opens an interactive dialog to view and edit UI, keybindings, and accessibility settings.
* **/theme** – Changes the CLI's visual appearance.
* **/stats** – Shows current session token usage, cached savings, and duration.
* **/clear** – Clears the terminal screen and visible session history.
* **/quit** or **/exit** – Exits the Gemini CLI session.

### 📁 Folder Awareness \& Context Injection

* **@<path>** – Injects the content of a file or directory into your prompt (e.g., `@src/` or `@docs/notes.md`).
* **! <command>** – Executes a system shell command directly from the Gemini prompt (e.g., `!dir` or `!mkdir`).
* **/directory** – Manages multiple directories in a workspace (sub-commands: `add`, `show`, `list`).
* **.geminiignore** – (File) Place in project root to exclude large folders (like `npm-cache/`) from being crawled.

### 🧠 Project Memory (GEMINI.md)

* **/init** – Scans your codebase to generate an initial `GEMINI.md` context file.
* **/memory show** – Displays the final, combined context from all loaded `GEMINI.md` files.
* **/memory refresh** – Reloads all `GEMINI.md` files after you've made manual edits.
* **/memory add <text>** – Quickly appends persistent instructions to your global memory file.

### 🔄 Session \& Project Management

* **/chat save <tag>** – Saves the current conversation state with a unique identifier.
* **/chat resume <tag>** – Resumes a previously saved conversation session.
* **/chat list** – Lists all available saved conversation tags.
* **/compress** – Replaces the entire chat context with an AI summary to save on tokens.
* **/restore \[id]** – Lists or restores project files to a state before a tool was executed (requires `--checkpointing`).
* **/share <file.md>** – Exports the current conversation to a Markdown or JSON file.

### ⌨️ Essential Keyboard Shortcuts (Windows)

* **Enter** – Submits the current prompt.
* **Tab** – Autocompletes file suggestions or accepts inline suggestions.
* **Up / Down Arrows** – Navigates through your previous input history.
* **Ctrl + C** – Clears the current input; press twice to quit the application.
* **Ctrl + L** – Clears the terminal screen and redraws the UI.
* **Ctrl + V** – Pastes clipboard content; automatically handles and references images.
* **Ctrl + X** – Opens your current prompt in an external editor for complex drafting.
* **Ctrl + S** – Toggles "copy mode" when in alternate buffer mode.
* **Ctrl + Y** – Toggles **YOLO mode** (auto-approval) for tool execution.
* **Esc (double press)** – Instantly clears the current input prompt.
