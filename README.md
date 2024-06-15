#Developer Environment Setup Guide.

##Table of Content.
1. Operating System.
2. Installation of IDE (Integrated Development Environment).
3. Set up VCS (Version Control System).
4. Necessary Programming Languages and runtimes.
5. Installation of Package Manager.
6. Configuration of Database (MySQL).
7. Set up a Development Environment.
8. Explore Extensions and Plugin.
9. Set up documentation.
10. Sample Project and Reflection.


1.#Operating System.
  I chose Microsoft Windows 11 as my operating system due to different reasons such, as very powerful performance, ease of upgrade, and very cheap to maintain.
  The Microsoft Windows can be purchased online at the official website https://www.microsoft.com/store or can be downloaded online at https://www.microsoft.com/en-us/software-download/windows11 or the third option is to update via Windows Settings if the computer 
  meets the requirements needed to move to Windows 11 if the user is using Windows 10.

##Installation Process.
  1. Windows issues guidance when updating via settings, easy to follow.
  2. A USB Flash Drive (Min.8GB Storage) required.
  3. Strong Connection to the internet.
  4. ###Download and run the Windows Media Creation Tool, choose "Create installation media," and select your USB flash drive.
  5. ###Insert the USB into the target PC, enter BIOS/UEFI settings (usually F2, F12, Delete, Esc), and set the USB as the primary boot device.
  6. ###Boot from the USB, select language/preferences, click "Install now," enter your product key, or skip if not available.
  7. ###Choose "Custom: Install Windows only," select the drive, and proceed with the installation.
  8. ###Complete Setup: Follow on-screen instructions to finalize the installation and activate Windows via Settings > Update & Security > Activation.

No issues with the process of Installing Microsoft Windows 11.

2.#Installation of IDE (Integrated Development Environment)
 1.##Visual Studio Code (VScode).
   Vscode offers a lot of experience to developers and is user-friendly, supports a lot of programming languages, and also plug-ins are available to make coding very simple
    Website: https://code.visualstudio.com/
 2.##Pycharm.
  I chose Pycharm to work on my Python projects, yes I have two IDEs, I was trying not to mix most of the projects that I work on and make it simple for me to access, I have them because I can debug code graphics, unique feature that associate it with Jupyter Notebooks
  Website: https://www.jetbrains.com/pycharm/

The installation process is very clean and simple to conduct.
1.###Pressing "Download" everything will be downloaded.
2.###Accessing downloaded files locally in the "Download Folder".
3.###Run the Software,exe as administrator and boom Install.

3.#Setting Up VCS (Version Control System).
  The popular VSC is Git, some everyone would choose it due to its speed, performance, and scalability, so I chose it as my VSC.

##Installation Process.
  1.###Website: https://www.git-scm.com/downloads
  2.###Open the downloaded .exe file and follow the setup instructions, accepting the default options unless you have specific needs. 
  3.###Open Gitbash to verify the installation by typing the following "git --version".
  4.###after type the following to configure (git config --global user.name "Your Name" , git config --global user.email "youremail@example.com")
    with the process I have mentioned, git will be ready to be used.

4. #Necessary Programming Languages and Runtimes.
   1. ##Node.js- I have installed it to be able to install and use the Vue.Js framework, well mostly for fronted Development, i have tried it, and it is not so bad for a beginner, yes I love it and hope to use it very often in future as I embark on my journey to be a software developer.
   ###Website: https://nodejs.org/en/download/package-manager.
   3. ##Python- my first language when I started programming as a self-taught, I made a calendar with Python and I loved it, because it was very simple as a beginner and very friendly.
   ###Website: https://www.python.org/downloads/.

Installation Process.

1.##Node.JS
  1.###Open the downloaded file and follow the installation instructions.
  2.###Open a terminal (or command prompt) and type node -v to check the installed Node.js version.
  3.###npm (Node Package Manager) comes with Node.js. Verify npm installation by typing npm -v.
  4.###npm install -g @vue/cli
  5.###vue create my-vue-app
  6.###cd my-vue-app
  7.###npm run serve
  8.###Everything is good to go with Node.JS and Vue.JS.

2.##Python 
  10.###Double-click the installer and follow the prompts.
  11.###Customize installation settings like installation directory and adding Python to PATH.
  12.###Open a command prompt or terminal and type python --version or python3 --version.
  13.###Type python or python3 in the command prompt or terminal to start using Python.

5.#Install Package Manager.
1.## I have two package managers in my laptop installed, NPM and PIP.

  ###NPM is for Node.Js
  1.####Installation: npm comes bundled with Node.js. Install Node.js from its official website.
  2.####Description: npm manages JavaScript packages for Node.js, allowing easy installation, update, and sharing of modules.
  3.####Usage: Use npm install <package-name> to install packages locally. For global installation, use npm install -g <package-name>.
  4.####Initialization: Use npm init to create a package.json file for managing project dependencies.
  5.####Example: To install the lodash library globally, use npm install -g lodash.

  ###PIP is for Python:
  1.####Installation: pip usually comes pre-installed with Python. Check its version with pip --version.
  2.####Description: pip is the default package installer for Python, enabling easy management of Python packages.
  3.####Usage: Use pip install <package-name> to install packages. For local installation, add --user.
  4.####Requirements File: Install packages listed in a requirements.txt file with pip install -r requirements.txt.
  5.####Example: To install the requests library, use pip install requests.

NO issue with the Package Manager process...

6.#Configuration Database (MySQL).
  A database where I will be likely to store data when I have built my Software as one of my projects and is very friendly to use and straightforward, I know a few basics, like Select, Where, Order by, and Create.
  Website: https://dev.mysql.com/downloads/windows/installer/8.0.html

  ##Installation Process
  1.###Follow the installation instructions provided for your operating system.
  2.###During installation, set up the root password and other configuration options as needed.
  3.###Optionally, configure additional settings such as networking, user accounts, and storage engines after installation.
  4.###Once installed and configured, MySQL can be interacted with via the MySQL command-line client or through graphical user interfaces like MySQL Workbench.
  5.###Use commands like mysql or mysql -u <username> -p to access the MySQL shell and execute SQL queries.
  6.###After installation and configuration, you can start MySQL and execute SQL queries to create databases, and tables, and manipulate data.

8.#Explore Extensions and Plug-in. 

##Vscode
   I have more than 350 Extensions installed in my Vscode but the ones that I use most are:
    1.###Prettier- to make my code clean and organized.
    2.###Live Server- to open my projects via a browser so I can navigate my work, especially using HTML and CSS.
    3.###Data Wrangler- to sort my data when I am busy with data analysis.
    4.###Auto Complete Tags- to complete tags for me when using HTML to save time.
    5.###Code Spell Checker- to help save time when debugging.

2.##Pycharm
  Just a few extensions:
     1.###Developer Tool-This plugin is a powerful and versatile set of tools designed to enhance the development experience for software engineers. With its extensive collection of features, developers can increase their productivity and simplify complex operations 
     without leaving their coding environment.
     2.###String Manipulation-Case switching, sorting, filtering, incrementing, aligning to columns, grepping, escaping, encoding...
     3.###Bash Support Pro-BashSupport Pro is an IDE for advanced Bash, POSIX, and Zsh script development – debugger, test runner, powerful editor, refactorings, ShellCheck, shfmt, and more.

10.#Sample Projects and Reflect.

1##My first project well more like checking if I am going in the right direction was just a clone copy of the Spotify Price Plan using HTML and CSS: https://github.com/Lasthope9/Price-Plan.git

2.##game of Rock/Paper/Scissors, my first well-coded mini-game as self-taught, before enrolling into Power Learn Academy, I achieved using HTML, CSS, and Javascript, but I am still rusty with Javascript: https://github.com/Lasthope9/Rock-paper-scissor-mini-game.git

Reflection:

Before Self-taught and PLP, I never thought I would achieve any of this, but now I am seeing a turning leaf, and I can actually do this.
  
    







