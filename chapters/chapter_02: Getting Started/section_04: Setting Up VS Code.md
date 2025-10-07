## 2.4 Setting Up VS Code

### 2.4.1 Exploring Code Editors: From CLI to Full IDE

Before diving into VS Code, it's helpful to understand the landscape of code editors. This section introduces different types of editors so geek kids can appreciate the flexibility of coding environments.

#### CLI Editors (Terminal-based):

* `nano`: A simple, beginner-friendly editor that works directly in the terminal.

* `micro`: A modern CLI editor with intuitive shortcuts and syntax highlighting.

* `vim`: A powerful editor with a steep learning curve, ideal for advanced users.

* `newvim`: A modern fork of Vim with better defaults, built-in plugin manager, and smoother onboarding for beginners.

#### GUI Simple Editors:

* `gedit`: Lightweight and pre-installed on Ubuntu, great for quick edits.

* `Kate`: A KDE-based editor with tabs, syntax highlighting, and session management.

#### Full IDEs:

* VS Code: Lightweight, extensible, and cross-platform. Ideal for beginners and pros alike.

* Qt Creator: Excellent for GUI-based C++ development.

* CLion: A commercial IDE with deep C++ support and smart code analysis.

**Geek Tip**: Try editing the same file in `nano`, `gedit`, and VS Code to feel the difference in workflow.

### 2.4.2 Why VS Code Is Perfect for Geek Kids

VS Code is the recommended editor for this book because it balances simplicity with power. Here's why it's a great choice:

* Free and open-source

* Works on Windows, macOS, and Linux

* Rich extension ecosystem for every language and tool

* Built-in terminal, Git integration, and debugging tools

* Easy to customize with themes and settings

* Seamlessly integrates with GitHub Codespaces — a cloud-based version of VS Code you can run entirely in your browser

### 2.4.3 Installing VS Code on Ubuntu

There are several ways to install VS Code on Ubuntu. Here's the easiest method:

#### Option 1: Ubuntu Software Center

* Search for "Visual Studio Code" and click install.

#### Option 2: Terminal (Recommended)

  ```
  sudo snap install code --classic
  ```

#### Option 3: Download from Official Website

* Visit [code.visualstudio.com](https://code.visualstudio.com) and download the `.deb` package. Once downloaded, you can install it using the terminal:
  ```
  sudo apt install ./code_*.deb
  ```
* Make sure you're in the directory where the `.deb` file was saved. You can use `cd ~/Downloads` if you downloaded it to your default folder. This command will install VS Code and handle dependencies automatically.

**Geek Tip**: Use `code --version` to verify installation and check which version of VS Code is installed — this works whether you installed it via Snap, apt, or a .deb package.

### 2.4.4 Setting Up C++ Extensions

To turn VS Code into a C++ development powerhouse, install the right extensions and configure build tasks.

* **Install C/C++ Extension Pack** by Microsoft





### 2.4.5 VS Code Tour and Shortcuts

Now that VS Code is installed and ready, let’s take a quick tour of its interface and learn some handy shortcuts to boost your coding speed

Main Interface Overview:

VS Code is made of several panels and windows that work together to help you write, organize, and run your code. Here's a beginner-friendly tour:

Activity Bar (Far Left Column):

This vertical bar lets you switch between different views like Explorer, Search, Source Control, Extensions, and more.

You can click each icon to open its related panel.

Explorer (📁):

Shows your files and folders.

You can open a folder to start working on a project.

Right-click to create new files or folders.

Editor Area (Center):

This is where you write and edit your code.

You can open multiple files in tabs, just like a web browser.

Side Bar (Left Panel):

Displays the contents of the selected Activity Bar icon (like Explorer or Extensions).

Status Bar (Bottom Strip):

Shows information like your current file type, Git branch, and errors or warnings.

You can click parts of it to change settings or view details.

Terminal (🖥️):

Built-in command line at the bottom of the window.

You can run commands like g++ hello.cpp or ls without leaving VS Code.

Extensions (🔌):

Lets you add new features and language support.

You can search for "C++" and install helpful tools.

Source Control (🔀):

Integrates with Git to track changes in your code.

You can commit, push, and pull code if you're using GitHub.

Command Palette:

Press Ctrl + Shift + P to open this powerful search bar.

You can type commands like "Change Theme" or "Install Extension".

Settings Panel:

Press Ctrl + , to open settings.

You can customize font size, theme, tab behavior, and more.

Geek Tip: You can resize panels by dragging their edges, and rearrange tabs to organize your workspace.



Useful Shortcuts for Geek KidCtrl + Shift + P: Open Command Palette — your gateway to all features.

Ctrl + B: Toggle the sidebar.

Ctrl + ~: Open or close the terminal.

Ctrl + /: Comment or uncomment a line.

Ctrl + Space: Trigger IntelliSense (auto-complete).

Ctrl + Shift + F: Search across all files.

Ctrl + Tab: Switch between open files.

Ctrl + Shift + E: Focus on Explorer view.

Ctrl + Shift + X: Focus on Extensions view.

Ctrl + Shift + G: Focus on Source Control view.

Geek Tip: Use the Command Palette to change themes, run tasks, or install extensions — it’s like magic for coder.



2.4.6 GitHub Copilot: Your AI Coding Assistant

GitHub Copilot is an AI-powered coding assistant that helps you write code faster and smarter. It works right inside VS Code, suggesting entire lines or blocks of code as you type.

🧠 What Is GitHub Copilot?

GitHub Copilot is trained on billions of lines of code and can:

Suggest code completions based on your comments and context

Help you write functions, loops, and even entire programs

Offer alternative solutions or fix bugs

Translate natural language into working code



⚙️ How to Install GitHub Copilot in VS Code

Open VS Code and go to the Extensions panel (Ctrl + Shift + X).

Search for GitHub Copilot.

Click Install.

Sign in with your GitHub account when prompted. If you don’t have a GitHub account yet, don’t worry — we’ll learn all about GitHub in the next chapters. You can activate GitHub Copilot later once you're ready.

Accept permissions and restart VS Code if needed.



🚀 Benefits of Using GitHub Copilot

Helps you learn by example — see how code is written

Speeds up repetitive tasks like loops and conditionals

Encourages exploration and creativity

Reduces frustration when you're stuck

Saves time while coding — Copilot can write boilerplate code instantly.

Explains code written by other programmers in a simple and fast way — great for understanding unfamiliar code.

Copilot offers around 2,000 free completions before requiring a subscription. This means you can try it out and generate short code suggestions without paying — perfect for beginners exploring its capabilities.

⚠️ Limitations to Keep in Mind

Copilot doesn’t always give correct or optimized code

It may suggest insecure or outdated patterns

You still need to understand and review the code it writes

GitHub Copilot is a paid service — students may get free access, but otherwise it requires a subscription.

Copilot has a limit characters per completion, so it may not generate long code blocks all at once.

The Copilot agent may pause or slow down if you make too many requests quickly — just wait a moment and try again.



Geek Tip: Always test and tweak Copilot’s suggestions. You’re the pilot — it’s just your copilot.

⌨️ Useful Shortcuts

Ctrl + Enter: Ask Copilot for a suggestion manually

Ctrl + I : start inline chat.

Tab: Accept Copilot’s inline suggestion

Esc: Dismiss a suggestion

Alt + \ : Requests a new suggestion at cursor

Alt + ]: Show next suggestion

Alt + [: Show previous suggestion

Ctrl + Alt + I : Open Chat view (side panel)

Ctrl + Shift + Alt + I: Switch to agent mode (chat)



Geek Tip: Use comments like // create a function to reverse a string and watch Copilot do the magic.

Geek Tip: GitHub Copilot Chat has three powerful modes: Ask, Edit, and Agent.

Ask: Use this mode to ask questions about your code, like "What does this function do?"

Edit: Use this mode to request changes, such as "Rename this variable" or "Add comments."

Agent: A special mode that lets Copilot act more like an assistant — it can follow instructions, perform tasks, and interact with your code more deeply.



⚠️ Tip: Don’t mix up the modes — each one is designed for a specific type of help. Use them wisely to get the best results!







2.4.7 Summary and Next Steps

You’ve now transformed VS Code into your personal C++ coding lab. Here’s what you’ve accomplished:

✅ Explored different types of editors

✅ Installed VS Code on Ubuntu

✅ Verified installation

✅ Added C++ extensions

✅ Learned the layout and shortcuts

➡️ Next Chapter: Writing Your First Real C++ Program*am
