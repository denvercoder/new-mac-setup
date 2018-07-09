# new-mac-setup

1. Browsers
    - Chrome
    - FireFox Developer Edition

2. iTerm 2
    - Setup your preferences however you like.
3. Alfred
    - (Optional) I like to use CMD + Space to activate so you need to turn off that key combo for spotlight.
      - System Preferences > Keyboard > Spotlight
      - Uncheck the two checkboxes    
    - Open Alfred
        - General > Launch Alfred at login
        - General > Alfred Hotkey: Set to CMD + Space
    - Powerpack users
        - Features > Clipboard: Check "Keep Plain Text", "Keep Images", "Keep File Lists"
4. Homebrew
    - First get command line tools for Xcode installed
        - Run the following command in your terminal `xcode-select --install`
        - enter this in the terminal and hit enter: 
            `ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
        - Add to path: `echo 'export PATH="/usr/local/bin:$PATH"' >> ~/.bash_profile`
        - `brew doctor`
        - `brew update`
5. Fira Code
    - Install Fira Code on your Mac (Optional)
    - Go to: https://github.com/tonsky/FiraCode/releases/download/1.205/FiraCode_1.205.zip
    - Select all Font Files in the TTF Folder. Right-click and select "Open with Font Book"
    - Click "Install Font"
6. iTerm config (Add Colors and Gittings)
    - Preferences > Profiles > Text
        - Click Change Font and either change to Fira or your preferred font.
    - Preferences > Profiles > Colors > Color Presets...
        - Select your favorite color scheme
    - Download the following files to your home directory
        - `cd ~`
        - `curl -O https://raw.githubusercontent.com/nicolashery/mac-dev-setup/master/.bash_profile`
        - `curl -O https://raw.githubusercontent.com/nicolashery/mac-dev-setup/master/.bash_prompt`
        - `curl -O https://raw.githubusercontent.com/nicolashery/mac-dev-setup/master/.aliases`
        - If you are using iTerm close it and open it or open a new tab with CMD + T and see in color!
7. Git
    - `brew install git`
    - change to home directory: `cd ~`
    - download the following gitconfig: 
        `curl -O https://raw.githubusercontent.com/nicolashery/mac-dev-setup/master/.gitconfig`
    - setup your user.name and user.email:
        `git config --global user.name "Your Name Here"`
        `git config --global user.email "your_email@youremail.com"`
    - If you would like to use your Mac keychain with git run:
        `git config --global credential.helper osxkeychain`
8. VS Code
    - 
















