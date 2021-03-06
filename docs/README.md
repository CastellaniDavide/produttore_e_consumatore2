# produttore_e_consumatore2
[![GitHub license](https://img.shields.io/badge/license-Apache%202.0%20License-green?style=flat)](https://github.com/CastellaniDavide/cpp-produttore_e_consumatore2/blob/master/LICENSE) ![Author](https://img.shields.io/badge/author-Castellani%20Davide-green?style=flat) ![Version](https://img.shields.io/badge/version-v02.01-blue?style=flat) ![Language Python](https://img.shields.io/badge/language-Python-yellowgreen?style=flat) ![sys.platform supported](https://img.shields.io/badge/OS%20platform%20supported-All-blue?style=flat) [![On GitHub](https://img.shields.io/badge/on%20GitHub-True-green?style=flat&logo=github)](https://github.com/CastellaniDavide/produttore_e_consumatore2) 

## Description
Producer and consumer with multiprocessing.
You can use this tool to get the files which are in a selected folder/ subfolder.

## Required
![](http://jeffnielsen.com/wp-content/uploads/2014/06/required-cropped.png)
 - choco/ apt

## Installation
![](https://dctacademy.com/wp-content/uploads/2016/12/install.jpeg)
 - choco (Windows) (as Administartor)
   - ```choco install produttore_e_consumatore2 --version=01.01```
 - Ubuntu using apt:
    - ```sudo add-apt-repository ppa:castellanidavide/school -y; sudo apt update; sudo apt install produttoreconsumatore2 -y```

### Update
![](https://images.idgesg.net/images/article/2020/07/software_update_by_gocmen_gettyimages-1146311500_2400x1600-100852481-large.jpg)
  - Windows (using choco):
    - ```choco upgrade produttore_e_consumatore2```
  - Ubuntu using apt:
    - ```sudo apt update; sudo apt upgrade```

### Delate
![](http://cdn.onlinewebfonts.com/svg/img_105952.png)
  - Windows (using choco):
    - ```choco remove produttore_e_consumatore2```
  - Ubuntu using apt:
    - ```sudo apt remove produttoreconsumatore2```

## Usage
 - with GUI
   - ![](https://raw.githubusercontent.com/CastellaniDavide/produttore_e_consumatore2/main/docs/GUI.png) Follow the labels (only folder one is obbligatory).
 - without GUI
   - produttore_e_consumatore2 [--batch | -b] - disable GUI mode
   - produttore_e_consumatore2 [--verbose] - verbose mode (if not in GUI mode)
   - produttore_e_consumatore2 [--csv] - enable csv output (if not in GUI mode)
   - produttore_e_consumatore2 [--folder] - enable csv output (if not in GUI mode)
   - produttore_e_consumatore2 [--url=... --token=... --table=...] - enable the upload to HarperDB (Replace "..." with the value(s)) (if not in GUI mode)

## Directories structure
![](https://cdn.analyticsvidhya.com/wp-content/uploads/2019/05/data-science-framework.png)
 - .gitignore
 - setup.py
 - LICENSE.md
 - .github
   - ISSUE_TEMPLATE
     - bug_report.md
     - feature-request.md
   - workflows
     - on-push.yml
     - on-release.yml
 - choco
   - set.txt
   - produttore_e_consumatore2.nuspec
   - tools
     - chocolateyinstall.ps1
     - chocolateyuninstall.ps1
     - LICENSE.txt
     - VERIFICATION.txt
 - debian
   - produttoreconsumatore2.1
   - produttoreconsumatore2.c
   - Makefile
   - requirements.in
   - debian
     - changelog
     - compat
     - control
     - copyright
     - postinst
     - postrm
     - preinst
     - rules
     - source
 - docs
   - logo.png
   - \*.md
 - flussi (example output(s))
   - net.csv
   - OS.csv
 - log (example log(s))
   - trace.log
 - requirements
   - requirements.txt
 - produttore_e_consumatore2
   - \_\_init\_\_.py
   
### Execution examples  
![](https://blog.toadworld.com/hs-fs/hubfs/SQL_tools-8_ways_large.jpg?width=3248&name=SQL_tools-8_ways_large.jpg)
 - produttore_e_consumatore2
   
### Output location
![](https://www.macroeconomia.it/wp-content/uploads/2018/03/input-output-650x364.png)
 - *.csv (if enabled) in the location where the code was lauched
 - *.log
   - C:/Program Files/produttore_e_consumatore2/* on Windows
   - ~/* on linux
   - current location (if you didn't lauch the code with the correct rights)

---
Made by Castellani Davide 
If you have any problem please contact me:
- help@castellanidavide.it
- [Issue](https://github.com/CastellaniDavide/produttore_e_consumatore2/issues)
