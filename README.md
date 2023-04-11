# Bitcoin_btp
Final year project based on Bitcoin. The repository implements **P2WPKH, P2WSH** and **P2TR** ( *both key and script path* ) 
 
## Setting Up


To get the most out of this book, you’ll want to create an environment where you can run the example code and do the exercises. Here are the steps required to set everything up:

### 1. Install Python 3.5 or higher on your machine:

Windows:		
[https://www.python.org/ftp/python/3.6.2/python-3.6.2-amd64.exe
](https://www.python.org/ftp/python/3.6.2/python-3.6.2-amd64.exe
)

macOS:		
[https://www.python.org/ftp/python/3.6.2/python-3.6.2-macosx10.6.pkg](https://www.python.org/ftp/python/3.6.2/python-3.6.2-macosx10.6.pkg)

Linux		
##### See your distro docs (many Linux distributions, like Ubuntu, come with Python 3.5+ preinstalled)

### 2. Install pip by downloading this script: [https://bootstrap.pypa.io/get-pip.py](https://bootstrap.pypa.io/get-pip.py).

### 3. Run this script using Python 3:

`$ python3 get-pip.py`		

### 4. Install Git. The commands for downloading and installing it are at [https://git-scm.com/downloads](https://git-scm.com/downloads).

### 5. Download the source code for this book:

`$ git clone https://github.com/crazyStarGazer/Bitcoin_btp.git`		
`$ cd Bitcoin_btp`
		
### 6. Install virtualenv:

`$ pip install virtualenv`

### 7. Install the requirements:

Linux/macOS

`$ virtualenv -p python3 .venv`		
`$ . .venv/bin/activate`
`(.venv) $ pip install -r requirements.txt`

Windows

`C:\Bitcoin_btp> virtualenv -p`		
`C:\PathToYourPythonInstallation\Python.exe .venv`		
`C:\Bitcoin_btp> .venv\Scripts\activate.bat`		
`C:\Bitcoin_btp> pip install -r requirements.txt`		
### 8. Run Jupyter Notebook:

`(.venv) $ jupyter notebook`




