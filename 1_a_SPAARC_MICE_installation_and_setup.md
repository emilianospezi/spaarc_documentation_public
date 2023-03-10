# SPAARC in MICE Toolkit: Installation & Setup

### [Back to Contents](README.md)

### [Video](videos/1_a_SPAARC_MICE_Toolkit_Installation.mp4)

## Overview
Set up custom environment for spaarc assuming a fresh installation of [MICE Toolkit](https://micetoolkit.com).

Assuming user has a premium licence for MICE Toolkit. 

## Installation  

#### 1. Download & Install WinPython 3.9 environment

- Download from: https://sourceforge.net/projects/winpython/
- Extract WinPython environment (default extracts in Download folder)
- Move WinPython folder in preferred location (e.g. C:\WPy64-39100 or C:\Programs\WPy64-39100) 

####  2. Collect requirements.txt from spaarc python code

- Alternatively, save the following in a new file called _requirements.txt_ :

    ```
    nibabel==3.2.2
    numba==0.55.0
    numpy==1.21.5
    pandas==1.4.0
    pytest==6.2.5
    scikit_image==0.19.1
    simpleitk==2.1.1
    #for windows try this if cannot find simpleitk version
    #simpleitk==2.1.1.1
    ```

####  3. Put requirements.txt into scripts folder of WinPython download

- WPy64-39100\scripts


####  4. Run _WinPython Command Prompt.exe_

- In WinPython command prompt, run:

    ```
    pip install -r requirements.txt
    ```

####  5. Point to custom python environment in MICE

- Go to Menu PLUGIN -> Python Settings -> use external interpreter and select python.exe from 
WPy64-39100\python-3.9.10.amd64 folder.


####  6. Import the mice plugin file located in spaarcpython directory (.plg) into MICE from the dropdown plugin menu

- When updated, the corefunctions should be copied into the plugin file inside MICE with the same name.  