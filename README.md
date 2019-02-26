# Setup Your Development Environment

### XCode
Download and install XCode from the AppStore

### Xcode Developer Tools
1. Open Terminal
2. Type `xcode-select --install`
3. From the popup prompt click the "Install" button

### Homebrew
1. Open Terminal
2. Type `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

### Create an empty bash_profile

```
touch ~/.bash_profile
```

### Install Ruby
```
brew update
brew install ruby

echo 'export PATH="/usr/local/opt/ruby/bin:$PATH"' >> ~/.bash_profile
```

### Install Node
1. `brew install node`

### Install Grunt
1. `npm install -g grunt-cli`

### Install Bower
1. `npm install -g bower`

### Install PIP
1. `sudo easy_install pip`

### Install Virtualenv
1. `sudo pip install virtualenv`

### Install MatPlot
1. `python3 -mpip install matplotlib`

### Install Numpy
1. `python3 -mpip install numpy`

### Install Pandas
1. `python3 -mpip install pandas`

### Install SciPy
1. `python3 -mpip install scipy`

### Install Seaborn
1. `python3 -mpip install seaborn`

### Install SASS
--------

### Setup VIM with
1. Open Terminal
2. Create new file at ~/.vimrc
3. Edit .vimrc
4. Use content from https://github.com/joshuapowell/.vimrc/blob/master/.vimrc to complete .vimrc

### Setup Cocoapods
1. `brew install cocoapods`

### Add Postgres App pg_config to path
1. Open Terminal
2. type `vi ~/.bash_profile`
3. Add `export PATH="/Applications/Postgres.app/Contents/Versions/latest/bin:$PATH"`
4. Save and close file

## Add Appropriate Authentication for Repository Access

### Add new SSH Key to Github
1. Go to https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/ and follow on screen instructions

# Other Applications to Install
- Google Drive File System
- 1Password
- Sketch
- Postgres.app
- PGCommander
- Google Chrome
- Slack
- CleanMyMac
- Realm Studio
- VPN
- Virus Scanner
- Microsoft Office
- PAW
- Invision Studio
- Arduino
- Fritzing
- Processing
- Grammarly
- Docker

