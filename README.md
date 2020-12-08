# create_venv
how to create venv in Windows10:
___________________________________
1) If you want to use PowerShell instead of cmd terminal you have to set the set-executionpolicy to unrestricted
For that open powerShell as admin:
Set-ExecutionPolicy -Scope CurrentUser
Execution Policy: Unrestricted
____________________________________
2) Create directory where you want to create your venv
3) create venv (pip install virtualenv)
in pwshell: python -m venv name_of_your_venv
4) clone the github repo
in pwshell: git clone https://github.com/robinrichermo/potfolio-app.git
5) Open your venv:
in pwshell: name_of_your_venv\Scripts\Activate.ps1
in pwshell, cd your new clode repo: cd potfolio-app
5) et voilà!
