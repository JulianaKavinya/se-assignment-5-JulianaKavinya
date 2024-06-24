[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15294983&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
   i. Download VS Code:
Go to the Visual Studio Code website.
Click the "Download for Windows" button. The download should start automatically.


ii. Install VS Code:
Once the download is complete, open the downloaded setup file (VSCodeSetup-x64-<version>.exe).
Follow the installation wizard steps:
Accept the license agreement.
Choose the destination location.
Select additional tasks such as creating a desktop icon and adding to PATH (recommended).
Click "Install" and then "Finish" once the installation is complete.

iii. Prerequisites
Windows 11 Operating System: Ensure you have Windows 11 installed and updated.
Administrator Rights: You might need administrator rights to install applications.


2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
i. Update Settings:
      Open VS Code.
      Go to File > Preferences > Settings (or press Ctrl+,).
      Adjust settings like font size, theme, and editor format according to my preferences.
ii. Install Extensions:
      Go to the Extensions view by clicking the Extensions icon in the Activity Bar on the side of the window or by pressing Ctrl+Shift+X.
      Search for and install essential extensions such as:
            -Prettier - Code formatter: Ensures consistent code formatting.
            -python - if you are using python language
            -Live Server: Provides a local development server with live reload.


3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
i. Activity Bar:
        Located on the far left side, it allows you to switch between views and gives access to various functionalities like Explorer, Search, Source Control, Run, and Extensions.
ii. Side Bar:
        Located next to the Activity Bar, it displays different views depending on the selected activity, such as file explorer, search results, or source control status.
iii. Editor Group:
       The central area where you can open, edit, and group multiple files. You can split the editor into multiple panes to view different files simultaneously.
iv. Status Bar:
          Located at the bottom of the window, it shows information about the current file, coding style, and errors/warnings.


4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
-The Command Palette provides a quick way to access all the commands in VS Code.
-Can be accessed  by pressing Ctrl+Shift+P or F1.
Examples of tasks:
Open Settings: Type Preferences: Open Settings.
Install Extensions: Type Extensions: Install Extensions.
Toggle Terminal: Type View: Toggle Integrated Terminal


5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
     -Extensions enhance the functionality of VS Code by adding new features.
Finding Extensions:
        - Click the Extensions icon in the Activity Bar or press Ctrl+Shift+X.
        -Search for desired extensions in the Extensions view.
Installing Extensions:
         -Click the Install button next to the desired extension.
Managing Extensions:
         -Go to the Extensions view.
         -Click on the installed extension to see details, settings, and options to disable or uninstall it.
Essential Extensions for Web Development;
          -Prettier - Code formatter
          -ESLint
          -Live Server
          -Path Intellisense
         -Debugger for Chrome


6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
i. How to Open and Use the Integrated Terminal
Open the terminal by pressing Ctrl+ or by selecting Terminal > New Terminal from the menu.
Use the terminal like a regular command-line interface within VS Code.
ii. Advantages of Using the Integrated Terminal;
       -Direct integration with the editor for easy access to files and commands.
       -Multiple terminal instances in one window.
       -Supports various shells like PowerShell, Command Prompt, and Git Bash.


7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
i. Create New File/Folder:
      -In the Explorer view, right-click and select New File or New Folder.
ii. Open File/Folder:
      -Click File > Open File or Open Folder.
iii. Navigate Between Files:
      -Use Ctrl+P to quickly open files by typing the file name.
      -Use the file explorer in the Side Bar.


8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
Settings Location:
      -Access settings via File > Preferences > Settings or Ctrl+,.
Changing Theme:
      -Search for Color Theme in the Command Palette and choose from available themes.
Changing Font Size:
      -In Settings, search for Font Size and adjust it.
Customizing Keybindings:
      -Go to File > Preferences > Keyboard Shortcuts or Ctrl+K Ctrl+S.


9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
-Open the Program:
-Open the file you want to debug.
-Set Breakpoints:
-Click in the gutter next to the line number where you want to set a breakpoint.
-Start Debugging:
-Press F5 to start debugging.
-Configure the launch.json file if needed.
-Debugging Features:
-Step Over (F10), Step Into (F11), Step Out (Shift+F11).
-Watch variables, call stack, and debug console.


10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
i. Initialize a Repository:
-Open the folder in VS Code.
-Click on the Source Control icon in the Activity Bar.
-Click Initialize Repository.
ii.Making Commits:
-Stage changes by clicking the + icon next to the changed files.
-Write a commit message and click the checkmark icon to commit.
iii. Pushing to GitHub:
-Set up a remote repository on GitHub.
-Use the terminal or the Source Control view to push changes:
-git remote add origin <repository-URL>
-git push -u origin main


## References
i.Visual Studio Code Documentation
ii.VS Code Extensions
iv.GitHub Documentation
v.class notes 



 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

