[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15294576&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

   USING UBUNTU 0S, THE FOLLOWING ARE THE STEPS TO FOLLOW :
sudo apt update - Updating System Packages
sudo apt upgrade
sudo apt install software-properties-common apt-transport-https wget -  Installing Required Dependencies
wget -q https://packages.microsoft.com/keys/microsoft.asc -O- | sudo apt-key add - Adding Microsoft’s GPG Key
sudo add-apt-repository "deb [arch=amd64] https://packages.microsoft.com/repos/vscode stable main" - Enabling the VS Code Repository
sudo apt install code - Install Visual Studio Code
Then Typing code to launch it for the first timr.

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
INITIAL CONFIGURATION AND SETTINGS ARE AS FOLLOWS;

 1.Theme and Appearance:
Go to File > Preferences > Color Theme and choose a preferred theme.
Adjust font size and type in File > Preferences > Settings by searching for "font size" and "font family".

 2.Extensions:
Install essential extensions like:
Python for Python development.
ESLint for JavaScript linting.
Prettier for code formatting.
Live Server for a local development server.

 3.Settings Sync:
Enable settings sync in File > Preferences > Settings Sync to sync settings across devices.

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
MAIN COMPONENTS OF VS CODE USER INTERFACE ARE ;
 1.Activity Bar:
Located on the left side, it provides access to different views like Explorer, Search, Source Control, Run and Debug, and Extensions.

 2.Side Bar:
Displays the contents of the selected view from the Activity Bar, such as file explorer, search results, or source control status.

 3.Editor Group:
The main area where you open and edit files. You can have multiple editors open in tabs.

 4.Status Bar:
Located at the bottom, it shows information about the current file, like language mode, Git branch, and errors/warnings.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

   COMMAND PALETTE ARE :
Accessing: Press Ctrl+Shift+P or F1.
Common Tasks:
Search and run commands (e.g., "Open File", "Save All").
Change settings (e.g., "Preferences: Open Settings (UI)").
Manage extensions (e.g., "Extensions: Install Extensions").


5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

EXTENSIONS IN VS CODE:
   Its roles is to enhance functionality, add language support, tools, and debuggers.
FINDING, INSTALLING, AND MANAGING EXTENSIONS:
 1.Find Extensions:
Click the Extensions icon in the Activity Bar or press Ctrl+Shift+X.
Search for desired extensions.

 2.Install Extensions:
Click the "Install" button next to the extension name.

 3.Manage Extensions:
View installed extensions under the "Installed" tab in the Extensions view.
Enable, disable, or uninstall extensions as needed.

ESSENTIAL EXTENSIONS FOR WEB DEVELOPMENT:
HTML, CSS, and JavaScript Support: IntelliSense and validation.
Live Server: Local development server with live reload.
ESLint: Linting for JavaScript and TypeScript.
Prettier: Code formatter

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
   OPENING AND USING INTEGRATED TERMINAL:

 OPENING TERMINAL:
Go to View > Terminal or press Ctrl+`.
The terminal appears at the bottom of the editor.

ADVANTAGES:
Direct access within the editor.
Multiple terminals with different sessions.
Integrated with project workspace.

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
 CREATING, OPENING, AND MANAGING FILES AND FOLDERS:

CREATE FILES/FOLDERS:
Right-click in the Explorer view and select "New File" or "New Folder".

 2.OPEN FILES/FOLDERS:
Click on files in the Explorer view.
Drag and drop files into the editor.

NAVIGATE BETWEEN FILES/DIRECTORIES:
Use the Explorer view.
Use Ctrl+P to quickly open files by name.

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
   FINDING AND CUSTOMIZING SETTINGS: 

Opening Settings:
Go to File > Preferences > Settings or press Ctrl+,

Changing Theme:
File > Preferences > Color Theme.

Changing Font Size:
Search for "Font Size" in the settings.

Changing Keybindings:
File > Preferences > Keyboard Shortcuts.

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

   SETTING UP AND STARTING DEBUGGING:
Open Debug View:
Click the Run and Debug icon in the Activity Bar.

Add a Configuration:
Click "create a launch.json file" and select the environment (e.g., Node.js).

Set Breakpoints:
Click in the gutter next to the line numbers.

Start Debugging:
Press F5 or click the green play button.

The Following are the Key Debugging Features:
Breakpoints.
Step through code.
Watch variables.
Inspect call stack.

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

INTEGRATING GIT WITH VS CODE ARE AS FOLLOWS:
Initialize Repository:
Open a folder in VS Code.
Go to the Source Control view and click "Initialize Repository".

Making Commits:
Stage changes by clicking the "+" icon.
Write a commit message and click the checkmark.

Pushing Changes to GitHub:
Set up the remote repository.
Use the terminal or Source Control view to push changes.

EXAMPLE OF COMMANDS:
bash
Copy code
git remote add origin https://github.com/username/repo.git
git push -u origin master

RESOURCES;
GitHub - https://resources.github.com/articles/
CodeCademy - https://www.codecademy.com/article/visual-studio-code
ChatGPT
Medium - https://blog.devgenius.io/the-reasons-why-you-must-use-visual-studio-code-b522f946a849

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

