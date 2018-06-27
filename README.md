# NOTES
## Just Notes on Env Setup etc

## GIT
```
Gitting started :)

My MAC all repos for GitHub  at cd ~/GIT/GITHUB/

git --version
git config -l
git config --global user.name "aj5158"
git config --global user.email "user@example.com"
git clone https://github.com/aj5158/RepoName.git

git remote show origin (ensure you are in the repo dir and .git file exists)

typically
git add (file or --all)
git status
git commit -a
git status
git push origin master


Add new Repo From command line
mkdir <repo name>
echo "# RepoName" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/aj5158/My-Bash.git
git push -u origin master

```

### Stash/BitBucket good Readme
https://www.atlassian.com/git


## HOMEBREW
### OSX application package manager (cf apt-get or yum)
```
NOTE: 
existing MAC OSX packages like sqlite, openssl etc when installed via brew are not symlinked into /usr/local


https://brew.sh/
Installed in ...
/usr/local/bin/brew
/usr/local/share/doc/homebrew
/usr/local/share/man/man1/brew.1
/usr/local/share/zsh/site-functions/_brew
/usr/local/etc/bash_completion.d/brew
/usr/local/Homebrew

use 
"brew install <package>"
brew install python3
brew upgrade python2
brew upgrade python3
brew help


# Opt out of analytics
brew analytics off
```  

## PYTHON ENVIRONMENT
### OSX
```
Get PIP
  python2 get-pip.py
  python3 get-pip.py

Then you can install Python packages with
  pip3 install <package>
To upgrade
  pip3 install --upgrade pip setuptools wheel

# Virtual Env
sudo pip install virtualenv


# API
install postman
as OSX APP
https://www.getpostman.com/apps

or via HomeBrew
#!/bin/bash
brew update                       # Fetch latest version of homebrew and formula.
brew tap caskroom/cask            # Tap the Caskroom/Cask repository from Github using HTTPS.
brew cask search postman          # Searches all known Casks for a partial or exact match.
brew cask info postman            # Displays information about the given Cask
brew cask install postman         # Install the given cask.
brew cask cleanup                 # For all installed or specific casks, remove any older versions from the cellar.
brew cleanup                      # For all installed or specific formulae, remove any older versions from the cellar.
# Visit https://www.code2bits.com
```
