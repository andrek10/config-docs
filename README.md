# How to configure multiple programs

# IPython
Scripts located in e.g. C:\Users\USERNAME\ipython\profile_default\startup\ are run automatically when IPython is initiated. .py files are python files, and use .ipy for ipython commands. To make qt5 matplotlib figures, clone qt5matplotlib.ipy inside this folder.

# LaTeX
## Latex Workshop in VSCode
Get SyncTex to work by copying kpathsea622.dll and synctex.exe into i.e. \MiKTeX 2.9\miktex\bin\x64.

# Inkscape
## Get LaTeX
Install pstoedit and ghostscript. Make sure both are in path. Latex and dvips should also be in path.

## Get LaTeX shortkey
Copy default.xml into C:\Program Files\Inkscape\share\keys