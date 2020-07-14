# Install_openslide
# How to install openslide module on Windows:

As I encountered various problems on the internet, regarding the installation of the openslide-module for python on windows systems, I wanted to share how it worked for me:

1. Install newest version of Windows Binaries from: https://openslide.org/download/#windows-binaries
2. Unzip the file and copy full path to your goal path
3. pip install openslide-python - in your goal venv, conda env, etc.
...
From now it depends which interpreter you use - hit the following commands:
1. Jupyter notebook:
- import os
- os.add_dll_directory(r'PATH')
- import openslide
2. Console:
- cd 'PATH'
- python
- import os
- os.add_dll_directory(r'PATH')
- import openslide


I got the idea from: https://stackoverflow.com/questions/59014318/filenotfounderror-could-not-find-module-libvlc-dll
