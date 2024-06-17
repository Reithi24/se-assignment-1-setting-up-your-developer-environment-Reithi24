[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15280235&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

Choosing the best OS depends on the specific requirements of the project and personal preferences, i therefore prefers Windows its strengths which includes;
(a) it has a wide compatibility with software and hardware.
(b) it has strong support for gaming and multimedia applications.
(c) its more popular in enterprise environments for productivity applications.

Steps involved in Download and Installation
(1) Check system requirements-ensure the PC meets the minimum system requirements for windows 11 eg RAM above 4GB,Storage 64 GB or larger storage device,TPM version 2.0
(2) Back Up your Data to an external drive or cloud
(3) Dowload Windows 11;if running windows 10, go to settings-updates-security and and windows update.check for updates  and if windows 11 available download and install.
(4) Install Windows 11
Using windows update ,follow the prompts to download and instal windows 11.
Your PC will restart several times during the installation process.


2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

Process involved for installing a Text Editor;vs code is my prefered IDE for my programming language.
Windows 
Go to the vs code website (https://code.visualstudio.com/Download),click on the download for windows button.
Run the downloaded installer and follow the setup wizard;locate the the file in downloaded folder and double click it.choose your installation preferences eg desktop icon and add vs code to your PATH.
Once installed ,lauch vs code from start menu or the desktop icon.


3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

A version control system(VCS) is a tool that helps software developers manage changes to source code over time,
They includes,Git,subversion(SVN),Mercurial

Installin Git in windows involves the following steps.
(a) Go to the git for windows website
(b) Click on the Download button to get the installer.
(c) Locate the downloaded installer and run it.
(d) Follow the setup wizard and leave most options at their default values.
(e) choose your preferred editor used by Git e.g VS code or Notepad
(f) Verify installation by opening Gitbash and type git --version. it will display git version
(g) Configure Git;set your username and user email.

Steps of creating a GitHub account

Open your web browser and go to the GitHub website,
Sign up your account and fill your username,email address and strong password,complete the registration process by confirming passwor.

Intitialize a Git Repository and making first commit
STEPS
Create a new repository on GitHub account
Fill in the repository name and add description(optional)and choose the visibility(public or private).
Check the box to initialize the repository with a README file and the click Create respository.
Clone the repository to your local machine
Navigate to the repository directory and make your first commit a s follows
           create a new file e.g "Hello world"
           Add the file  git add .
           git commit-m "Hello world"
           git push


4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

Steps involved
(1) Install Python and Run the download and check or click the "Add Python to PATH"
    Select install Now or customize installation for advanced options and verify installation.
(2) Install python package manager(pip)
(3) Setting up virtual Environment which allow to create isolated python environment for the projects.
(4) Install Additional Compliers and interpreters; (c/c++ compliiers)
(5) Install integrated Develpment Environment(IDE)
(6) Configuration and Customization
(7) Troubleshooting by ensuring python and pip are added to the PATH.


5. Install Package Managers:
   If applicable, install package managers like pip (Python).
 A package manager simplifies the installation ,updating and management of software packages.
 Steps involved in installation
 Windows
 Install python and pip
 Download python installer by downloading the latest version
 Run the download installer,check Add python to PATH and click install Now and follow instructions.
 Verify installation by.
 opening cmd and type  python --version and also 
 Verify pip by typing pip --version


6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

Steps involved for windows
(a) Download MySQL Installer for windows and click the Download button.
(b) Locate the downloaded installer and double click it to run it.
(c) Choose the setup type(Developer Default),click next and follow the instructions.
(d) During the installation ,you will be prompted to configure the MySQL server by choosing a server type,setting up the password and then configuring the MySQL service to start automaticaly.
(e) Once configuration is complete click "Finish" to complete the installation process.
(f) Verify installation by log using the root user and password to set configuration.
     mysql -u root -p if prompt is seen then insatllation is successful.


7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

Steps involved
Windows
(1) Downlod Docker Desktop and install
     Double click the download and follows instructions.
     Once the installation is complete ,start Docker Desktop fro the start menu.
(2) Manage Docker as a Non Root User,create the docker group and add your user
(3) Enable and start the Docker service
(4) Verify Docker installtion
(5) Set Up a Development Environment with Docker by creating the followings;
     -Create a project Directory
     -Create a Dockerfile
     -Create a Requirement File
     -Create an Application File
     -Bulid the Docker Image
     -Run the Docker Container
(6) Customizing your Development Environment through;
    - Installing the Docker extenssion for VS code to manage Docker containers and images directly from the editor.
    - Automating tasks using Make file to automate common development tasks.


8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

They include;
(a) Visual Studio cODE(vs Code), the extnsions include
     - Language support which includes; pytho,Javascript,HTML/CSS,C++,Java and PHP
(b) Code Quality and Formatting which includes;ESLint,Prettier,Markdown Lint.
(c) Productivity which includes; Live Server,Gitlens and Bracket Pair Colorizer 2.
(d) Development Utilities which includes; Docker,Remote(SSH),Remote-containers.Jupyter.
(e) Themes and UI Customization which includes Dracula official ,Material Theme,Icon Theme etc


9.  Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 
    Steps involved:

     (1) Install Essential Tools,these includes
          (a) Visual studio code(VSO), IDEs,Git
     (2) Install and configure python and pip and verify installation
     (3) Instal MySQL Database and configure MySQL.
     (4) Configure Develpment Environment e.g Git and code editor
     (5) Set up Virtual Environments for python ie install virtualenv,create and activate virtual environment.
     (6) Install additional tools 
     (7) Troubleshooting commonissues includes,
        - PATH issues,ensure that python ,pip and other tools are added to the PATH
        - Permission issues,run as administrator for installations that require permission
        - Dependency conflicts,use virtual environments to manage dependencies and avoid conflicts between the projects.
   - (8) Customize Environment for productivity,the involves
   -      - Recommend extensions
   -      - Customize Terminal or Git bash
   -      - Configure SSH keys for GitHub.


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
Challeges faced with;
-unable to screenshot and attached to my answers
