[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15274001&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

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

SOLUTION

How to Download and Install Windows 11

Step 1: Check System Requirements

Before you begin, ensure your PC meets the minimum system requirements for Windows 11. These include a compatible 64-bit processor, 4GB RAM, 64GB storage, UEFI firmware with Secure Boot, TPM version 2.0, DirectX 12 compatible graphics, and an HD display greater than 9” with 720p resolution.

Step 2: Download Windows 11

1.	Go to the Microsoft Windows 11 Download Page:
   Visit Microsoft Windows 11 Download.

2.	Download the Installation Media:
   Choose the method you prefer to create Windows 11 installation media. You can either download the Installation Assistant, Create Windows 11 Installation Media, or Download Windows 11 Disk Image (ISO).

Step 3: Create Installation Media

1.	Using the Installation Assistant:
   Run the Installation Assistant and follow the prompts to upgrade directly to Windows 11.
2.	Using Media Creation Tool:
   Run the tool, accept the license terms, and select Create installation media (USB flash drive, DVD, or ISO file) for another PC.
   Select the language, edition, and architecture, then choose your media (USB flash drive or ISO file).

Step 4: Install Windows 11

1.	Insert Installation Media:
   If using a USB flash drive or DVD, insert it into your PC.
2.	Boot from Installation Media:
   Restart your PC and boot from the USB or DVD. This usually requires changing the boot order in the BIOS/UEFI settings.
3.	Install Windows 11:
   Follow the on-screen prompts to install Windows 11. Choose your preferences, and when prompted, enter your product key or select I don't have a product key.

4.	Set Up Windows 11:
   Once installation is complete, follow the setup instructions to configure your preferences, connect to the internet, and create or log into your Microsoft account.

![alt text](image.png)
By following these steps, you can successfully download, install, and set up Windows 11 on your PC. For more details, visit the Microsoft Windows 11 Download Page.

How to Install Visual Studio Code

Step 1: Download Visual Studio Code
   
   1.	Go to the Visual Studio Code download page.
   2.	Select the appropriate version for your operating system:
   
   Windows: Choose between User Installer or System Installer.

Step 2: Install Visual Studio Code

For Windows:
   1.	Run the Installer:
      Locate the downloaded file (e.g., VSCodeUserSetup-x64-<version>.exe) and double-click it to run the installer.
   2.	Setup Wizard:
      
      Accept the license agreement and click Next.
      Choose the destination folder and click Next.
      Select additional tasks such as creating a desktop icon and associating file types, then click Next.
      Click Install.
   3.	Launch Visual Studio Code:
      Once the installation is complete, click Finish to launch Visual Studio Code.
      ![alt text](image.png)

How to Set Up Git and GitHub

Step 1: Install Git

![alt text](image.png)

For Windows:
   1.	Download Git:
      Go to the Git download page.
      Download the latest version of Git for Windows.
   2.	Run the Installer:
      Locate the downloaded .exe file and double-click it.
   Follow the installation prompts, keeping the default options unless specific changes are needed.

Step 2: Configure Git
   1.	Set Up Global Configuration:
      Open Terminal (or Git Bash on Windows) and configure your username and email:
      git config --global user.name "Your Name"
      git config --global user.email "your.email@example.com"
   
   2.	Verify Configuration:
      Check your settings by running:
      git config --list

Step 3: Create a GitHub Account
   1.	Sign Up for GitHub:
   ![alt text](image.png)
      
   Go to the GitHub sign-up page.
   Fill in your details, choose a username, and create an account.

Step 4: Initialize a Git Repository
   1.	Navigate to Your Project Directory:
      Open Terminal or Git Bash and navigate to your project folder:
      cd path/to/your/project

   2.	Initialize the Repository:
      Run the following command to initialize a new Git repository:
      git init

   3.	Add Files and Make Your First Commit:
      Add your project files:
      git add .

     Commit the changes:
     git commit -m "Initial commit"

Step 5: Push to GitHub
   1.	Create a New Repository on GitHub:
      Go to GitHub and click on the + icon in the top right corner.
      Select New repository, name it, and click Create repository.
   ![alt text](image.png)

   2.	Link Local Repository to GitHub:
      -  Copy the repository URL provided by GitHub.
      -  In Terminal or Git Bash, run: 
   git remote add origin https://github.com/yourusername/your-repository.git
   git branch -M main
   git push -u origin main

   3. Initialize Repository: 
   4. Create New Repository: 
By following these steps, you can successfully install and configure Git, create a GitHub account, initialize a repository, and make your first commit.


How to Install Python and Set Up Your Environment

Step 1: Download Python

1.	Go to the Official Python Website:
![alt text](image.png)
   -	Visit Python.org.  

2.	Download the Installer:
   -  Click on the "Downloads" tab.
   -  Select the version appropriate for your operating system (Windows, macOS, Linux). 

Step 2: Install Python
![alt text](image.png)

For Windows:
1.	Run the Installer:
   Locate the downloaded file (e.g., python-<version>-amd64.exe) and double-click it.
2.	Setup Wizard:
   Check the box for "Add Python to PATH".
   Click on "Install Now".
   Follow the prompts to complete the installation.
3.	Verify Installation: 
   Open Command Prompt and type: 
![alt text](image.png)

Step 3: Install Necessary Tools
   1.	pip (Python Package Installer):
   	pip is included with Python 3.4+.
   Verify by typing:
   ![alt text](image.png)

   2.	Virtual Environment (venv):
      Create a virtual environment for your project:
   ![alt text](image.png)
   
   Activate the virtual environment:
   Windows: 
   ![alt text](image.png)

Step 4: Install Project Dependencies
   1.	Using pip:
      With your virtual environment activated, install necessary packages:
      pip install package-name
   2.	Requirements File:
      If your project has a requirements.txt file:
      pip install -r requirements.txt
By following these steps, you can successfully install Python, set up a virtual environment, and install necessary packages for your project.

Step 1: Download MySQL Installer

Visit the MySQL download page for Windows: https://dev.mysql.com/downloads/windows/installer/5.7.html
![alt text](image.png)

Click on the "Download" button for the MySQL Installer.

Step 2: Run MySQL Installer
   -  Once the download is complete, run the MySQL Installer executable.
   -  Select the "Custom" installation type and click "Next".

Step 3: Select Components

In the "Select Products and Features" screen, select the following components:
-  MySQL Server
-  MySQL Workbench
-  Connector/ODBC

Click "Next".
![alt text](image.png)

Step 4: Configure Server Settings

In the "Configure Server Settings" screen:
   -  Enter a root password for MySQL.
   -  Choose a port number (default is 3306).
   -  Select the "TCP/IP" protocol and click "Configure".
   -  Verify that the IP address is set to "0.0.0.0" (allows connections from any IP address).
   -  Click "OK" and then "Next".
 ![alt text](image.png)

Step 5: Install

Review the installation settings and click "Install".
The installation process will begin.

Step 6: Post-Installation

Once the installation is complete, click "Finish".

Open MySQL Workbench and create a new database and tables as needed.
![alt text](image.png)
![alt text](image.png)

By following these steps, you can download, install, and configure MySQL on your Windows machine. This setup will allow you to manage and interact with MySQL databases effectively.

How to Explore Extensions and Plugins for Visual Studio Code

Visual Studio Code (VS Code) is a versatile text editor with a wide range of extensions and plugins available to enhance its functionality. Here's a detailed guide on how to explore and install these extensions.

Step 1: Open Extensions View
   1.	Open VS Code:
      Launch Visual Studio Code.
   2.	Navigate to Extensions:
      Click on the Extensions icon in the Activity Bar on the side of the window. Alternatively, you can press Ctrl+Shift+X (Windows/Linux) or Cmd+Shift+X (macOS).
 
Step 2: Explore Extensions
   1.	Search for Extensions:
      Use the search bar to find specific extensions. For example, type "Python" to find extensions related to Python development.
   2.	Browse Categories:
      Browse through categories like "Popular", "Installed", "Recommended", etc.

   ![alt text](image.png)

Step 3: Install Extensions
   1.	Select an Extension:
      Click on an extension to view details, reviews, and documentation.
   2.	Install the Extension:
      Click the Install button.
   3.	Reload VS Code:
      Some extensions might require reloading VS Code. Click the Reload button if prompted.

   ![alt text](image.png)

Step 4: Configure Extensions
   1.	Access Extension Settings:
      -  Click the gear icon next to the installed extension and select Extension Settings.
   2.	Configure Settings:
      -	Modify settings as per your requirements.
 
Recommended Extensions

1.	Python: Enhances Python development with IntelliSense, linting, and debugging.
2.	ESLint: Integrates ESLint JavaScript code linting.
3.	Prettier: Code formatter supporting various languages.
4.	GitLens: Provides Git superpowers inside VS Code.
5.	Docker: Adds support for Docker container development.

By following these steps, you can explore and install extensions to enhance your coding experience in Visual Studio Code. For more information, visit the Visual Studio Code Marketplace.


Challenges Faced During MySQL Installation

Incomplete Installation

One significant challenge encountered during the installation of MySQL was dealing with an incomplete installation. Specifically, the MySQL Workbench, a crucial tool for database management, was missing. This incomplete installation posed several difficulties and required manual configuration to resolve.

Cause: The incomplete installation can result from various issues such as missing dependencies, interrupted installation process, or compatibility problems.

Solution:
Re-run the Installer: To address the missing MySQL Workbench, you can re-run the MySQL installer. During the installation process, ensure that all necessary components, including MySQL Workbench, are selected.

Steps:
-  Open the MySQL Installer.
-  Navigate to the product catalog.
-  Select MySQL Workbench and other necessary components.
-  Proceed with the installation.
-  Manual Configuration: If re-running the installer does not resolve the issue, you may need to manually download and configure MySQL Workbench.

Steps:
-  Download the MySQL Workbench installer from the official MySQL website.
-  Run the installer and follow the prompts to complete the installation.
-  Once installed, configure MySQL Workbench to connect to your MySQL server by adding a new connection with the appropriate credentials.
-  Detailed Steps for Manual Configuration:

Download MySQL Workbench:
-  Go to the MySQL Workbench download page and download the installer for your operating system.
-  Install MySQL Workbench:
-  Run the downloaded installer file and follow the on-screen instructions to install MySQL Workbench.
-  Ensure all necessary dependencies are installed during this process.

Configure MySQL Workbench:
-  Open MySQL Workbench.
-  Click on the + icon to add a new connection.
-  Enter the necessary connection details such as hostname (usually localhost), port (default is 3306), username (default is root), and password.
-  Click on Test Connection to ensure that MySQL Workbench can connect to your MySQL server.
-  Save the connection and start managing your databases.

Common Issues and Troubleshooting:

Dependency Issues: Ensure that all required dependencies are installed. MySQL Workbench requires certain libraries and runtime environments to function correctly.

Compatibility Issues: Verify that the version of MySQL Workbench you are installing is compatible with your operating system and MySQL server version.

Resources:
MySQL Installation Guide
MySQL Workbench Manual

By following these steps, you can address the challenge of an incomplete MySQL installation and successfully install and configure MySQL Workbench for your database management needs. 






 


