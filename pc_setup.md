# Setup 
This file allows to easily setup a new OS used for genomics and other applications
## OS independant installations
[Notable](https://github.com/notable/notable)  
[Zotero](https://www.zotero.org/download/)  
[VS Code](https://code.visualstudio.com/)

## VS code extensions
[Gitlens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)  
[Spell check](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)

## Linux distro
[Lubuntu](https://lubuntu.net/)

## Important WSL commands
Before installing WSL permissions in windows need to be set. Run following command as admin in power shell.
```
Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux
```  
Run VS code in WSL mode.  
```
code .
```
Terminal emulator:  
[ConEmu](https://www.fosshub.com/ConEmu.html)  
[vcxsrv](https://sourceforge.net/projects/vcxsrv/)  
Make sure to save correct display variable by adding following variable to your bashrc:  
```DISPLAY=:0.0```  


## Miniconda itself and packages
[Miniconda Python 3.7](https://docs.conda.io/en/latest/miniconda.html)
IPython:  
```conda install -c anaconda ipython```    
Numpy:  
```conda install -c anaconda numpy```  
Jupyter:  
```conda install -c anaconda jupyter```   
Matplotlib:  
```conda install -c conda-forge matplotlib```  
Zlib for C compiling:  
conda install -c anaconda zlib

## apt-get installs
Update WSL before us.  
```sudo apt-get update```  
Installing make, used for installing github repos.  
```sudo apt-get install build-essential```  
Zlib for C compiling:
```sudo apt-get install libz-dev```  
 
## Genomic packages
https://github.com/lh3/minimap2
