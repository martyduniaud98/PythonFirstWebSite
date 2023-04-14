# Fist Simple Python Web Project
Simple python web project with mysql, html, css, js, bootstrap

## Sommary
1. [Install python3 and other tools](#install-python3-and-other-tools)
    a. [Windows](#for-windows)<br>
    b. [Ubuntu](#for-ubuntu)<br>
    c. [MacOs](#for-macos)  <br>
2. [Virtualenv (optional)](#virtualenv-optional)<br>
    a. [Windows](#windows)<br>
    b. [Ubuntu](#ubuntu)<br>
    c. [MacOs](#macos)<br>
3. [Download Docker image](#download-docker-image)<br>

<br>

### Install python3 and other tools

Try `python3 -v` on terminal/powershell to check if python3 is installed on your system, if installed pass to the next step.

- For Windows
    - https://www.python.org/downloads/windows/

- For Ubuntu
    - `sudo apt install python3`

- For MacOs
    - `brew install python3`

<br>

### Virtualenv optional
*This step is optional, you can skip if you don't want to use virtualenv.*
On Terminal/Powershell run the following commands to install virtualenv and create a virtual environment for the project

- Windows
    ```
    pip install virtualenv
    cd PythonFirstWebSite
    virtualenv venv
    env\Scripts\activate
    ```

- Ubuntu
    ```
    sudo apt install python3-venv
    cd PythonFirstWebSite
    python3 -m venv venv
    source venv/bin/activate
    ```

- MacOs
    ```
    pip3 install virtualenv
    cd PythonFirstWebSite
    virtualenv venv
    source venv/bin/activate
    ```


<br>

### Download Docker image
if you préfère use docker image, you can download it from [lien a mettre]
