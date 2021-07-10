# PythonSandbox
Python virtual environment with Docker

## Environment
Windows  
[Docker Desktop for Windows](https://hub.docker.com/editions/community/docker-ce-desktop-windows/)  
[Visual Stdio Code](https://azure.microsoft.com/ja-jp/products/visual-studio-code/)  
[Remote-Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)  
[VcXsrv](https://sourceforge.net/projects/vcxsrv/)  

## Python version
3.9.6

## Python libraries
matplotlib  
numpy  
seaborn  
pandas  
flake8  
autopep8  
pytest  

## How to use
### 1. Launch VcXsrv
execute xlaunch.exe  
![](docs/img/display_settings.PNG)  
![](docs/img/client_startup.PNG)  
![](docs/img/xtra_settings.PNG)  
![](docs/img/finish_configuration.PNG)  

### 2. Open root directory with VSCode
Open root directory of this repository with VSCode  
![](docs/img/open_root_directory.PNG)  

### 3. Open folder in container  
Click the following icon  
![](docs/img/open_remote_window.PNG)  

When you open for the first time, select "Open Folder in Container"  
![](docs/img/open_folder_in_container.PNG)  

Select this repository's folder  
![](docs/img/select_this_folder.PNG)  

### 4. Build container
Building container will start  
![](docs/img/starting_container.PNG)  

After buidling, installing python libraries will start  
![](docs/img/pip_install.PNG)  

Installation will finish as follow  
![](docs/img/install_finish.PNG)  

### 5. Confirmation
Open terminal and confirm Python's version  
![](docs/img/terminal_python_version.PNG)  

Execute sample code  
The following graph window will be shown  
![](docs/img/sample_code.PNG)  