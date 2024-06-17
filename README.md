[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15281358&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

Below is a link  to the Documentation containing the questions below :
https://docs.google.com/document/d/13rqbVS_cnDscdc6tLlEhvOwqlzKBzh_jBdBw6-BlEFI/edit

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

     Answer:
         Step 1: Open the Web browser (Google Chrome)
         Step 2: Go to the Visual Studio Code Website
         Step 3: On the download page, click on the "Download for Windows" button. This will download the installer for Windows.
         Step 4 : Once the download is complete, open the downloaded file (typically named something like " VSCodeUserSetup-x64-<version>.exe)" .
         Step 5 : Start the Installation
         Step 6 : Accept the License Agreement
         Step 7 : Choose the destination folder where you want to install VS Code. The default location is usually fine.
         Step 8 : Select Additional Tasks
         Step 9 : Install the Software
         Step 10 : Complete the Installation

      The prerequisites that may be needed include:
           1. Windows 11 Operating System
           2. Administrative rights to install software on your machine.
           3. Internet Connection that is required to download the installer.


2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

   Answer:

       INITIAL CONFIGURATION:
         1. Open VS Code
         2. Open a folder or create a new workspace.
         3. Configure Settings.
             (i)  Go to Settings
             (ii) Font Size: Set a comfortable font size, e.g., 14.
             (iii) Tab Size: Set the tab size, e.g., 2 or 4 spaces.
             (iv) Format On Save: Enable this setting to auto-format your code on save.
             (vi) Auto Save: Set to afterDelay or onWindowChange for automatic saving of files.
             (v) Workbench: Color Theme: Choose a theme you find comfortable, such as Dark+ or Light+.
         4. Install Key Extensions.
            (i) Go to the Extensions view by clicking the square icon on the sidebar.
            (ii) Install prettier - Code formatter: For consistent code formatting.
            (iii) Install live Server: For launching a local development server with live reload feature for static & dynamic pages.
            (iv) Install auto Rename Tag: Automatically renames paired HTML/XML tags.
            (v) Install gitLens: Enhances the built-in Git capabilities.
         5. Set up Version Control
         6. Configure User and Workspace Settings. User settings apply globally across all projects, while workspace settings apply to the specific project.

      CUSTOMIZING THE USER INTERFACE.
         1. You can move the side bar (Explorer, Search, Source Control, etc.) to the right side by right-clicking the activity bar and selecting "Move Side Bar Right".
         2. Enable or disable the minimap (a small overview of your code) in View > Appearance > Show Minimap.
         3. Customize the status bar by right-clicking it and selecting or deselecting options as needed.

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

     Answer:
         1. Activity Bar
          It is located vertically on the far left side of the window.
          The Activity Bar provides access to different views and functionalities in VS Code. Each icon on the Activity Bar represents a different view or extension.
            Example: 
              (i) Explorer - Access and manage files and folders in your workspace.
              (ii) Search - Performs text searches across files in your project.
              (iii) Source Control - Manage source control repositories (e.g., Git).
              (iv) Run and Debug - Start and control debugging sessions.
              (v) Extensions - Discover and install extensions to enhance VS Code.

         2. Side Bar
           It is located directly to the right of the Activity Bar.
           The Side Bar displays the contents of the currently selected view in the Activity Bar.
             Example:
             (i) If the Explorer view is selected, the Side Bar will display a file explorer.
             (ii) If the Search View is selected it provides a search interface for finding text in your files.
             (iii) If the Source Control View is selscted,it displays version control information and allows you to perform source control operations.
             (iv) If the Run and Debug View is selected it will show debugging controls and information about running processes.
             (v) If the Extensions View is selected, it will show a list of installed extensions and offers recommendations for new extensions.

         3. Editor Group
            It is located at the Central area of the window, taking up the majority of the space.
            The Editor Group is where you write and edit your code. It can be split into multiple editors.
            You can open multiple files in separate editors.
               Examples:
               (i)  Tabs: Each open file is represented by a tab. You can switch between tabs to navigate through open files.
               (ii) Split Editor: You can split the editor into multiple panes (horizontal or vertical) to view and edit files side by side.
               (iii) Code Editor: The main area where you write and edit your code, with features like syntax highlighting, IntelliSense (code suggestions), and linting.
         
         4. Status Bar
            It is located horizontally along the bottom of the window.
            The Status Bar displays information about the current file or project, such as the file type, line.
            It also provides quick access to certain commands and settings.
              Examples:
              (i) File encoding and line endings.
              (ii) Git branch and repository information.
              (iii) Language mode and file type.
              (iv) Errors and warnings count.
             (v)  Quick access to commands like "Save All" and "Toggle Word Wrap".


4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
        
        Answer:
           -> A command palette is a powerful feature in Visual Studio Code (VS Code) that provides quick access to a wide array of commands and functionalities without the need for navigating through menus. 

           ->How to Access the Command Palette
            Keyboard Shortcut: Press Ctrl + Shift + P or F1.
            Menu Access: Click on View in the menu bar and select Command Palette.

            -> Common tasks using the command palette:
               (i) File Operations:
                  Open File: Start typing "Open File" and select the command to open a file.
                  Save File: Type "Save" to quickly save the current file.
                  Close File: Type "Close Editor" to close the current file.

               (ii) Editing and Navigation:
                  Go to Line: Type : followed by the line number (e.g., :42) to navigate to a specific line in the file.
                  Toggle Sidebar Visibility: Type "Toggle Sidebar Visibility" to show or hide the sidebar.
                  Split Editor: Type "Split Editor" to divide the editor into multiple panes for side-by-side coding.

               (iii) Source Control:
                  Git: Clone: Type "Git: Clone" to clone a repository from a URL.
                  Git: Commit: Type "Git: Commit" to commit changes with a message.
               
               (iv) Search and Replace:
                  Find in Files: Type "Find in Files" to open the search functionality.
                  Replace in Files: Type "Replace in Files" to perform a search and replace operation across files.

               (v) Extensions:
                  Install Extensions: Type "Extensions: Install Extensions" to browse and install new extensions.
                  Disable Extensions: Type "Extensions: Disable" to disable a specific extension.


5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

