## 2.5: Writing Your First Program

Welcome to your first real adventure in C++! In this chapter, you'll write your very first program using three different tools: Nano (a terminal editor), gedit (a graphical editor), and VS Code (a powerful code editor). You'll also learn how to compile your code, understand basic syntax, and explore what makes real geeks tick.

### 2.5.1 What Are You About to Do?

Before you start typing, let’s understand what’s happening behind the scenes. This step is about building your mental model of how programming works:

* A **C++ program** is a set of instructions written in a language your computer understands — but only after it's translated.

* **Compiling** is like translating your code from C++ into machine language (binary), so your computer can actually follow your instructions.

* **Running** your program means executing those instructions — your computer does exactly what you told it to do.

Think of it like writing a recipe (your code), turning it into a dish (compiling), and then tasting it (running). Each step helps you understand how your ideas become real actions on your machine.

### 2.5.2: Write Your First Program in Nano

Nano is a simple text editor you use from the terminal — a command-line interface (CLI) that lets you talk directly to your computer using text commands. It might look old-school, but it's still used by professionals and geeks everywhere because it's fast, lightweight, and always available — even on remote servers or minimal systems.

Why do we still use terminal tools like Nano? Because they give you full control, teach you how things really work, and help you understand your system deeply. Plus, they’re great for scripting, automation, and working without distractions.

Other CLI editors include:

* **vim** — powerful and fast, but has a steep learning curve.

* **emacs** — customizable and feature-rich, often used by advanced developers.

* **micro** — a modern terminal editor with easier controls.

*  **newvim** — a modern fork of Vim with better defaults, built-in plugins, and smoother onboarding for beginners.

Here’s how to write your first program using Nano:

1. Open your terminal.
   Shortcut tip: On Ubuntu, press `Ctrl + Alt + T` to open the terminal instantly. This works on most Linux systems and is a great way to get comfortable using the command line quickly.

2. First, create a folder to keep your code organized. In the terminal, type:
   ```
   mkdir -p ~/Documents/my_code/cpp_code/hello_world
   cd ~/Documents/my_code/cpp_code/hello_world
   ```
   This is just an example — you can create your folder anywhere you like!  Here's what they do:
   * `mkdir -p` creates the full folder path, including any missing parent folders.

   * `cd` changes your current location to that folder so you can start working there.
   Feel free to choose a different name or location if you prefer — the key is to keep your projects tidy and easy to find.
3. Now, type `nano hello.cpp` to create a new file. You can name your code file anything you like — such as `main.cpp`, `test.cpp`, `first_code.cpp`, or `my_project_001.cpp`. Just make sure it ends with `.cpp` so the compiler knows it's a C++ source file.

4. Type this code:
   ```
   #include <iostream>
   int main() {
       std::cout << "Hello, Geek!" << std::endl;
   return 0;
   }
   ```
5. Save and exit:
   * Press Ctrl + O to save.
   * Press Enter to confirm.
   * Press Ctrl + X to exit.
6. Compile your code:
   ```
   g++ -o hello_app hello.cpp
   ```
   note that the order doesn't matter as long as the output name follows -o.

   you can compile your code also with this:
   ```
   g++ hello.cpp -o hello_app
   ```

7. Run your program:
   ```
   ./hello_app
   ```

### 2.5.3 Try It in gedit

If you prefer a graphical editor, gedit is a great starting point. It’s part of the GNOME desktop environment and offers a clean, simple interface for writing code. GUI (Graphical User Interface) tools like gedit are part of what makes modern operating systems friendly and accessible — they let you interact with your computer using windows, buttons, and menus instead of just text commands.

GUI systems include tools like file explorers, editors, and browsers — all designed to make computing easier and more visual. gedit is one of many GUI-based editors. Others include Notepad++ (Windows), Kate (KDE), and even online editors like [repl.it](https://repl.it) or [GitHub Codespaces](https://github.com/features/codespaces).

Here’s how to use gedit:

1. Before you open gedit, make a directory for your code and navigate into it. This helps keep your projects organized and easy to find.

    ```
    mkdir -p ~/Documents/my_code/cpp_code/hello_world
    cd ~/Documents/my_code/cpp_code/hello_world
    ```
    You can create your folder anywhere you like — this is just an example. The mkdir -p command creates the full folder path, and cd moves you into that folder so you're ready to work.

2. Now, open gedit:
   ```
   gedit hello.cpp
   ```
3. Write this code.
   ```
   #include <iostream>
   int main() {
       std::cout << "Hello, Geek! (from G-edit)" << std::endl;
   return 0;
   }
   ```
4. Save the file.
5. Compile and run using the same terminal commands.
   ```
   g++ -o hello_app hello.cpp
   ./hello_app
   ```
**Geek Tip**: You can write your code anywhere — in gedit, Nano, VS Code, or even in a browser-based editor.
**IDEs (Integrated Development Environments)** like **VS Code** or **CLion** make coding more comfortable with features like auto-complete, syntax highlighting, and debugging tools. But remember: a true geek kid should be able to write code in any environment.

**Weekly Challenge**: Once a week, write a simple C++ program using only a basic text editor like Nano or gedit — no IDE features. This will help you see how well you’ve really learned the syntax and structure of the language. It’s like practicing with training wheels off — and it makes you stronger!
















💻 Step 4: Try It in VS Code

VS Code is a powerful editor with lots of features:

Open VS Code and create a new file named hello.cpp.

Paste your code.

Open the terminal inside VS Code (`Ctrl + ``).

Compile and run your code.

Explore the interface: file explorer, terminal, extensions.





🎨 Step 5: Code Format vs. Functionality

Code formatting makes your code easier to read.

Try removing indentation and see if it still works.

Fix it and notice how much cleaner it looks.


```
#include <iostream>
int main(){std::cout<<"Hello, Geek!"<<std::endl;return 0;}
```

🖱️ Step 6: Real Geeks Don’t Use Mice

Learn keyboard shortcuts:

Nano: Ctrl + O, Ctrl + X, arrow keys.

VS Code: Ctrl + S, Ctrl + Shift + P, `Ctrl + ```.

Practice doing everything without the mouse.





⚙️ Step 7: Compile with g++ and Explore Flags

Try these commands:

g++ -E hello.cpp → Shows preprocessed output.

g++ -S hello.cpp → Shows assembly code.

g++ -c hello.cpp → Creates an object file.

g++ hello.cpp -o hello → Creates the final executable.

Each step is part of the build process. You’re learning how your code becomes a real program.

🧪 Step 8: Experiment!

Change the message in cout.

Add another line of output.

Break the code on purpose and fix it.

✅ Summary

You’ve now written, compiled, and run your first C++ program in three different editors. You’ve explored formatting, shortcuts, and build flags. You’re officially a geek coder in action!w keys.

