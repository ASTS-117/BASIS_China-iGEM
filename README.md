
  
## Getting started

You should probably only edit the files inside folders `static`, `wiki` and `wiki > pages`.
1. Open the Web IDE
1. Make the changes on the files you wish:
    * For the menu, change the file [menu.html](wiki/menu.html)
    * For the layout, change the file [layout.html](wiki/layout.html)
    * For the pages, change the corresponding file in the foler [pages](wiki/pages)
1. Review the changes you made
1. Once you are done, save the changes by **committing** them to the *main branch* of the repository
1. An automated script will build, test and deploy your wiki, which should take less than 30 seconds.

## About this Template

### Files

The static assets are in the `static` directory. The layout and templates are in the `wiki` directory, and the pages live in the `wiki > pages` directory. Unless you are an experienced and/or adventurous human, you probably shouldn't change other files.

    |__ static/             -> static assets (CSS and JavaScript files only)
    |__ wiki/               -> Main directory for the pages and layouts
        |__ footer.html     -> Footer that will appear in all the pages
        |__ layout.html     -> Main layout of your wiki. All the pages will follow its structure
        |__ menu.html       -> Menu that will appear in all the pages
        |__ wiki-tools.html -> Wiki tools to help getting started with this template
        |__ pages/          -> Directory for all the pages
            |__ *.html      -> Actual pages of your wiki
    |__ .gitignore          -> Tells GitLab which files/directories should not be uploaded to the repository
    |__ .gitlab-ci.yml      -> Automated flow for building, testing and deploying your website.
    |__ LICENSE             -> License CC-by-4.0, all wikis are required to have this license - DO NOT MODIFY
    |__ README.md           -> File containing the text you are reading right now
    |__ app.py              -> Python code managing your wiki
    |__ dependencies.txt    -> Software dependencies from the Python code

## Getting Started Locally

### MacOS

1. Install [Visual Studio Code](https://code.visualstudio.com/sha/download?build=stable&os=darwin-universal)
1. Install [Python](https://www.python.org/ftp/python/3.11.2/python-3.11.2-macos11.pkg)
   * After you download and go through the install, open the **Terminal** and type `python3 --version`. It should show some numbers on the next line. This confirms that the installation was successful.

### Windows Setup Process

1. Install a code editor or IDE from the below list:
   * [Visual Studio Code](https://code.visualstudio.com/sha/download?build=stable&os=win32-x64-user) - most professional and functional, but harder to learn and use
   * [Sublime Text](https://www.sublimetext.com/download_thanks?target=win-x64) - simple and clean interface with most functions you need
2. Install [Python](https://www.python.org/ftp/python/3.11.2/python-3.11.2-amd64.exe)
   * As you go through the installer, make sure you check "Add Python to PATH" and "Disable path length limit." [more help](https://www.tomshardware.com/how-to/install-python-on-windows-10-and-11)
   * Open **Command Prompt** (Win+R, type in "cmd.exe") and type `python3 --version` or `python --version' to confirm. If it does not give you a version number, find me.
4. Fork the master repo (https://github.com/drasimov/BASIS_China-iGEM)
5. If you are not using Git (see below), manually download the .zip file of the master repo
5. Right-click the file "win-setup.ps1" in the BASIS_China-iGEM folder and click "Run with Powershell"

## Optional Git workflow
1. Install [Git](https://github.com/git-for-windows/git/releases/download/v2.39.2.windows.1/Git-2.39.2-64-bit.exe)
   * Open **Command Prompt** (Win+R, type in "cmd.exe") and type `git --version` to confirm. 
   * Run `git config 
  
