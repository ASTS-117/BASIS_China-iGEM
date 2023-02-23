## Files

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

## MacOS Setup Process


4. Fork the master repo (https://github.com/drasimov/BASIS_China-iGEM) to your Github account
5. If you are not using Git (see below), manually download the [.zip file](https://github.com/drasimov/BASIS_China-iGEM/archive/refs/heads/main.zip) of the master repo. Note that if you are not using Git, you will have to do this again each time the master repo is edited.
6. 

### Optional Git workflow
1. Install [Git] (https://sourceforge.net/projects/git-osx-installer/files/git-2.15.0-intel-universal-mavericks.dmg/download)

## Setup Process

1. Install a code editor or IDE from the below list:
   * Visual Studio Code: [Windows](https://code.visualstudio.com/sha/download?build=stable&os=win32-x64-user) [MacOS](https://code.visualstudio.com/sha/download?build=stable&os=darwin-universal) - most professional and functional, but harder to learn and use
   * Sublime Text: [Windows](https://www.sublimetext.com/download_thanks?target=win-x64) [MacOS](https://www.sublimetext.com/download_thanks?target=mac) - simple and clean interface with most functions you need
2. Install **Python** [Windows](https://www.python.org/ftp/python/3.11.2/python-3.11.2-amd64.exe) [MacOS](https://www.python.org/ftp/python/3.11.2/python-3.11.2-macos11.pkg)
   * For Windows, As you go through the installer, make sure you check "Add Python to PATH" and "Disable path length limit." [more help](https://www.tomshardware.com/how-to/install-python-on-windows-10-and-11)
   * Open Windows **Command Prompt** (Win+R, type in "cmd.exe") or Apple **Terminal** and type `python3 --version` or `python --version' to confirm. If it does not give you a version number, the installation failed, find me later.
4. Fork the master repo (https://github.com/drasimov/BASIS_China-iGEM) to your Github account
5. If you are not using Git (see below), manually download the [.zip file](https://github.com/drasimov/BASIS_China-iGEM/archive/refs/heads/main.zip) of the master repo. Note that if you are not using Git, you will have to do this again each time the master repo is edited.
6. Unzip the folder where you want to work. I suggest placing the folder on the Desktop.
   * On Mac, double click the folder to unzip. On Windows, click "Compressed Folder Tools" in the top bar and "Extract All"
5. Right-click the file "win-setup.ps1" (it is inside the BASIS_China-iGEM folder) and click "Run with Powershell"

### Optional Git workflow
1. Install [Git](https://github.com/git-for-windows/git/releases/download/v2.39.2.windows.1/Git-2.39.2-64-bit.exe)
   * Open **Command Prompt** (Win+R, type in "cmd.exe") and type `git --version` to confirm. 
   * Run `git config --global user.name XXX` (XXX is your github username) and `git config --global user.email XXX` (XXX is your github email)
2. Make sure you have completed steps 1-4 from above.
3. Navigate to your repository page (yourusername/BASIS_China-iGEM), copy the link in the browser
4. In **Command Prompt** type `cd Desktop` if you want to work on the desktop, and enter `git clone` and paste the link you copied. Hit enter.
5. Right-click the file "win-setup.ps1" (it is inside the BASIS_China-iGEM folder) and click "Run with Powershell"
