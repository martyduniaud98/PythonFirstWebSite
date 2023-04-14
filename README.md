# Fist Simple Python Web Project
Simple python web project with mysql, html, css, js, bootstrap

## Sommary
1. [Install python3 and other tools](#install-python3-and-other-tools)
    a. [Windows](#Windows)<br>
    b. [Ubuntu](#Ubuntu)<br>
    c. [MacOs](#Macos)  <br>
2. [Install virtualenv (optional)](#virtualenv-(optional))<br>
    a. [Windows](#Windows)<br>
    b. [Ubuntu](#Ubuntu)<br>
    c. [MacOs](#MacOs)<br>
3. [Download Docker image](#download-docker-image)<br>

<br>

### Install python3 and other tools

Try `python3 -v` on terminal/powershell to check if python3 is installed on your system, if installed pass to the next step.

- Windows
    - https://www.python.org/downloads/windows/

- Ubuntu
    - `sudo apt install python3`

- MacOs
    - `brew install python3`

<br>

### Virtualenv (optional)
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
