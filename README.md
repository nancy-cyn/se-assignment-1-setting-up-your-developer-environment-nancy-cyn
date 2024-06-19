[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15265488&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:
 
##### 1. Select Your Operating System (OS):
Choose an operating system that best suits your preferences and project requirements.
* _Check System Requirements:_ Ensure your PC meets the minimum system requirements for Windows 11. You can find these requirements [on the Windows 11 specifications page](https://www.microsoft.com/en-us/windows/windows-11-specifications).

* _Visit the Windows 11 Download Page:_ Open your web browser and go to the [Windows 11 download page](https://www.microsoft.com/software-download/windows11).
* _Backup Your Data:_ Backup your important files to avoid data loss during the installation process.
* _Download the Installation Assistant:_ Click on the "Download Now" button under the "Windows 11 Installation Assistant" section.
![Image of Window 11 download page](/Screenshots/Screenshot%202024-06-19%20094451.png)

* _Run the Installation Assistant:_ Locate the downloaded file, usually in the "Downloads" folder. For safety select the default for all configurations.
* _Complete the Installation:_ After the installation, your computer will restart several times. Follow the prompts to complete the setup, including configuring your user account, regional settings, and privacy settings.



##### 2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. 
* _Visit the Visual Studio Code Download Page:_ Open your web browser and go to the [Visual Studio Code download page.](https://code.visualstudio.com/Download)
![Image of Visual Studio Code download page](/Screenshots/Screenshot%202024-06-19%20101704.png)
* _Download Visual Studio Code:_ Choose the appropriate download link for your operating system (e.g., Windows, macOS, or Linux). In my case I had choose Windows.
* _Run the installer:_ Double-click the .exe file you downloaded. If prompted by User Account Control (UAC), click "Yes" to allow the installation.
* _Follow the Installation Prompts_
   * Agree to the license terms: Read the license agreement, check the box to accept the agreement, and click "Next".
   * Select the destination folder: Choose the folder where Visual Studio Code will be installed or use the default location. Click "Next".
   * Select additional tasks:
      * Check "Create a desktop icon" if you want a shortcut on your desktop.
      * Check "Add to PATH" if you want to be able to open VS Code from the command line.
      * Check "Add Open with Code action to Windows Explorer file context menu".
      * Check "Add Open with Code action to Windows Explorer directory context menu".
      * Click "Next".
      * Install: Click "Install" to start the installation process.
      * Finish the installation: Once the installation is complete, check "Launch Visual Studio Code" and click "Finish" to open VS Code.

##### 3. Set Up Version Control System:
   Install Git and configure it on your local machine.
   * _Visit the Git Download Page:_ Open your web browser and go to the [Git download page.](https://git-scm.com/download/win)
   * _Download the Installer:_ Choose the appropriate download link for your operating system. In my case I choose 64-bit Git Window Setup
   ![Image of Git download page](/Screenshots/Screenshot%202024-06-19%20103347.png)
* _Run the Installer:_ Locate the downloaded file, run it and follow the installation prompts.

Create a GitHub account for hosting your repositories. 
* _Open Git Bash:_ Open Git Bash from the Start menu or command line.
* _Set Up Your Username and Email:_ 

         git config --global user.name "nancy-cyn"
         git config --global user.email "kabobo.nancy44@gmail.com"
* _Visit GitHub to Create an Account:_ Go to [GitHub](https://github.com/) and sign up for a new account and use the same email and username from Git Bash

Initialize a Git repository for your project and make your first commit. 
* _Create a New Directory and initialize a Git repository:_
   ![Image of Git Bash creating and initializing ](/Screenshots/Screenshot%202024-06-19%20115828.png)
* _Create and Add a README File and Commit Changes:_
   ![Image of Git Bash commiting changes ](/Screenshots/Screenshot%202024-06-19%20120009.png)


##### 4. Install Necessary Programming Languages and Runtimes:
* Open your web browser and go to the [Python website](http://wwww.python.org).
   ![Image of Python download page ](/Screenshots/Screenshot%202024-06-19%20120758.png)
* Install Python that is compatible with your operating system. 
* _Run the Installer:_ Locate the downloaded file and run it.
When done add the python to path via envirnoment variable.
* _Verification:_ Open Command Prompt or Git Bash and run:

        python --version
 

##### 5. Install Package Managers:
* _Verify Pip Installation:_ Pip is included with Python. Verify by running

      pip --version


##### 6. Configure a Database (MySQL):
* Open your web browser and go to the [MySQL download page.](https://dev.mysql.com/downloads/windows/installer/5.7.html)
   ![Image of MySQL download page ](/Screenshots/Screenshot%202024-06-19%20121654.png)

* Install MySQL that is compatible with your operating system. 
* _Run the Installer:_ Locate the downloaded file and run it.
When done add the python to. Use the default(recommended settings). Configure the MySQL Server settings, including setting up a root password.Make sure you have the root password saved somewhere as you will need it login in regularly.
* _Verify the Installation:_ Go to gitbash and insert:

      mysql --version
* Login using your root password with this command: 

      mysql -u root -p


##### 7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

##### 8. Explore Extensions and Plugins:
* Click on the Extensions icon in the Activity Bar to explore available extensions, plugins, and add-ons. 

   * Such as Python to develop Python projects.
   ![Image of Python extension page ](/Screenshots/Screenshot%202024-06-19%20123652.png)
   * Such as Dart to develop Dart projects.
   ![Image of Dart extension page ](/Screenshots/Screenshot%202024-06-19%20124412.png)
   * Such as Markdown Preview Enhanced to view README files before they are pushed to github
   ![Image of Dart extension page ](/Screenshots/Screenshot%202024-06-19%20124608.png)
   * Prettier to help format my code
   ![Image of Prettier extension page ](/Screenshots/Screenshot%202024-06-19%20123740.png)
 

##### 9. Document Your Setup:
Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

##### 10. Reflection on challengees faced
I had difficulty installing Python due to an incorrect PATH configuration, which caused the python command to be unrecognized in the terminal. To resolve this, I reinstalled Python and ensured the option to add Python to PATH was selected during the installation.

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
