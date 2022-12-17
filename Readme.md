# Python file: aulaglobal.py
Replace the NIA with your number, or replace it by an input.
Python small program to download all the files available in the AulaGlobal repository, from the university Carlos III of Madrid
This code is not mine, below this paragraph is the original readme.


# Python client to UC3M Aula Global
This small python script allows you to download all the content from your [UC3M Aula Global](http://aulaglobal.uc3m.es) courses (.pdf, .docx, .pptx, etc.). It works as a crawler, checking the site for files as if it was you with your browser.

## Usage
Download the repository as zip, clone it with git, or just use curl to get only the script. On GNU/Linux or MacOS:
```
curl -o aulaglobal.py "https://raw.githubusercontent.com/tairosonloa/Aula_Global_UC3M/master/aulaglobal.py"
pip3 install --user -r requirements.txt
python3 aulaglobal.py
```
## Requirements
Python version 3.7 or above is required to run the script. Also, you'll need two libraries: `mechanize` and `beautifoulsoup`.

Most of GNU/Linux distributions call the python package as "python3". To install dependences on Debian based GNU/Linux distros (Ubuntu, Linux Mint, ...):
```
sudo apt-get install python3 python3-pip
pip install -r requirements.txt
```
To install dependences on MacOS:
```
xcode-select --install
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew install python3
python3 get-pip.py
pip3 install --user -r requirements.txt
```
## License
This script is under [MIT license](https://github.com/tairosonloa/Aula_Global_UC3M/blob/master/LICENSE).
