[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15294840&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

Setting Up My Environment for the Power Learn Project (PLP)

Table of Contents:
1. Select Your Operating System (OS)
2. Install a Text Editor or Integrated Development Environment (IDE)
3. Set Up Version Control System
4. Install Necessary Programming Languages and Runtimes
5. Install Package Managers
6. Configure a Database (MySQL)
7. Set Up Development Environments and Virtualization (Optional)
8. Explore Extensions and Plugins
9. Document Your Setup
10. Sample Project and Reflection








1. Select Your Operating System (OS)

Choose an operating system that matches your preferences and project requirements. I opted for Windows 11.

-Download and Install Windows 11:
Follow the instructions provided on the [Windows 11 download page](https://www.microsoft.com/en-us/software-download/windows11).

2. Install a Text Editor or Integrated Development Environment (IDE)

Select and install a text editor or IDE that suits your programming needs and workflow. I chose Visual Studio Code for its user-friendly interface.

-Download and Install Visual Studio Code:
Get it from the [Visual Studio Code download page](https://code.visualstudio.com/).

3. Set Up Version Control System

Install Git and configure it on your local machine. If you don’t have one, create a GitHub account for hosting repositories. Initialize a Git repository for your project and make your first commit.

- Install Git:
  - Windows: Download the Git installer from [git-scm.com](https://git-scm.com/) and follow the installation instructions.

  - Configure Git:
    
    git config --global user.name "Your Name"

    git config --global user.email "your.email@example.com"
    

- Create a GitHub Account:
Sign up at [GitHub](https://github.com/).

-Initialize a Git Repository:

    mkdir my-project

    cd my-project

    git init

    echo "# My Project" > README.md

    git add README.md

    git commit -m "Initial commit"

    git branch -M main

    git remote add origin https://github.com/yourusername/my-project.git

    git push -u origin main

 4. Install Necessary Programming Languages and Runtimes

Install the programming languages required for your project along with their compilers, interpreters, or runtimes.

-Install Python: Download it from the [official Python website](https://www.python.org/downloads/).

  -Steps:
    - Run the installer and follow the instructions.
    - Ensure you check the option to add Python to your PATH during installation.
5. Install Package Managers

Install package managers needed for your programming languages, such as `pip` for Python.

- Steps:
  - Verify `pip` installation:
    pip --version
    ```
  - Upgrade `pip` if necessary:
    python -m pip install --upgrade pip
    ```

6. Configure a Database (MySQL)

Download and install MySQL.

- Download MySQL:** Get it from the [MySQL Installer page](https://dev.mysql.com/downloads/installer/).

  - Steps:
    - Download the MySQL Installer.
    - Run the installer and follow the on-screen instructions.
 7. Set Up Development Environments and Virtualization (Optional)

Explore virtualization tools to create isolated development environments. Although I’m not very familiar with virtualization, here are some tools you can consider:

- Tools:
  - [Docker](https://www.docker.com/get-started)
  - [VirtualBox](https://www.virtualbox.org/)

 8. Explore Extensions and Plugins

Install the following extensions and plugins to enhance your development environment in Visual Studio Code:

- Extensions and Plugins:
  - [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
  - [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
  - [Prettier - Code Formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
  - [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
  - [Code Runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner)
  - [Live Preview](https://marketplace.visualstudio.com/items?itemName=ms-vscode.live-server)
  - [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
  - [Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens)
 Reflection

This process was made very straightforward and easy to follow, the dificulties only occured when installing visualcode because my laptop was not used to running complicated apps like it. Visualcode would not open easily for the first few times and i had to re download it.
