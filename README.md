# Assignment: Setting Up Your Developer Environment

## Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

Tasks and Detailed Steps:

### 1. Select Your Operating System (OS)
#### Task: Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11.

#### Steps:
1. Download Windows 11:
   - Visit [Microsoft's Windows 11 download page](https://www.microsoft.com/software-download/windows11).
   - Click on the "Download Now" button to download the installation assistant.

   ![Windows 11 Download](/screenshots/screenshot1.png)

2. Install Windows 11:
   - Open the downloaded installation assistant and follow the on-screen instructions to upgrade your current OS to Windows 11.
   - Ensure your system meets the hardware requirements for Windows 11.

   ![Windows 11 Installation](/screenshots/screenshot2.png)

Errors and Debugging:
Compatibility Issues: my laptop does not support windows 11 and hence i opted to maintain windows 10
- Installation Stuck:Restart the installation process or check for troubleshooting tips on the Microsoft support site.

 2. Install a Text Editor or Integrated Development Environment (IDE)
Task: Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code (VS Code).
Steps:
1. Download VS Code:
   - Visit the [Visual Studio Code download page](https://code.visualstudio.com/Download).
   - Select the appropriate version for your OS and click "Download".

   ![VS Code Download](/screenshots/screenshot3.png) 

2. Install VS Code:
   - Run the downloaded installer and follow the installation steps.
   - Choose any additional options you prefer (e.g., adding VS Code to PATH).

   ![VS Code Installation](/screenshots/screenshot4.png) 


 3. Set Up Version Control System
Task: Install Git, configure it on your local machine, create a GitHub account, initialize a Git repository for your project, and make your first commit.

Steps:
1. Install Git:
   - Visit the [Git download page](https://git-scm.com/downloads).
   - Download and install Git for your operating system.

   ![Git Download](/screenshots/screenshot5.png) 

2. Configure Git:
   - Open a terminal or command prompt and set your username and email:
     ```sh
     git config --global user.name "ELIZANGINA"
     git config --global user.email "nginae415@gmail.com"
     ```

   ![Git Config](/screenshots/screenshot6.png) 
   - Visit [GitHub](https://github.com) and sign up for a new account 

   ![GitHub SignUp](/screenshots/screenshot7.png) 

4. Initialize a Git Repository:
   - Navigate to your project directory and initialize a Git repository:
     ```sh
     git init
     ```

5. **Make Your First Commit:**
   - Create a sample file (e.g., `README.md`), add it to the repository, and commit:
     ```sh
     echo "# My Project" > README.md
     git add README.md
     git commit -m "Initial commit"
     ```

   ![First Commit](/screenshots/screenshot9.png) 


 4. Install Necessary Programming Languages and Runtimes
Task: Install Python and ensure you have the necessary tools to build and execute your code.

Steps:
1. Download Python:
   - Visit the [Python download page](https://www.python.org/downloads/).
   - Download the latest version of Python for your operating system.

   ![Python Download](/screenshots/screenshot10.png) 

2. Install Python:
   - Run the downloaded installer and ensure you check the option to "Add Python to PATH".
   - Follow the installation steps.

   ![Python Installation](/screenshots/screenshot11.png)


### 5. Install Package Managers
**Task:** Install package managers like pip (Python).

**Steps:**
1. **Verify pip Installation:**
   - Pip should be installed automatically with Python. Verify by running:
     ```sh
     pip --version
     ```

   ![Pip Version](/screenshots/screenshot12.png) 

2. **Install Packages:**
   - Install necessary Python packages using pip:
     ```sh
     pip install <package-name>
     ```

   ![Pip Install](/screenshots/screenshot18.png)


 6. Configure a Database (MySQL)
Task: Download and install MySQL database.

Steps:
1. Download MySQL:
   - Visit the [MySQL download page](https://dev.mysql.com/downloads/windows/installer/5.7.html).
   - Download the MySQL Installer for Windows.

   ![MySQL Download](/screenshots/screenshot13.png) 




3. Configure MySQL
   - During installation, set up your root password and other configurations.

   ![MySQL Configuration](/screenshots/screenshot13.png) 




Steps:
1. Install Docker:
   - Visit the [Docker download page](https://www.docker.com/products/docker-desktop) and download Docker Desktop for your OS.

   ![Docker Download](/screenshots/screenshot14.png)

2. Install VirtualBox :
   - Visit the [VirtualBox download page](https://www.virtualbox.org/wiki/Downloads) and download the installer for your OS.

   ![VirtualBox Download](/screenshots/screenshot15.png) 

3. **Configure and Run Containers:**
   - Follow Docker's tutorials to set up and run containers.

   ![Docker Running](/screenshots/screenshot16.png) 



 8. Explore Extensions and Plugins
Task: Explore available extensions, plugins, and add-ons for your chosen text editor or IDE.

Steps:
1. Install Extensions in VS Code:
   - Open VS Code and go to the Extensions view by clicking the Extensions icon in the Activity Bar.
   - Search for and install desired extensions (e.g., Python, GitLens, Prettier).

   ![VS Code Extensions](/screenshots/screenshot17.png) 

