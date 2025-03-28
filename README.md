# COMM2216-Final-Assignment

# Required
1. Python (3+)
2. pip
3. virtualenv 
4. Terminal that supports Bash commands (e.g. Bash, ZSH, PowerShell)

# How to Run
1. Go to the project directory.
2. Open the terminal in the project directory.
3. In the terminal type
```bash
virtualenv venv
source venv/bin/activate
```
for Linux-based systems (MacOS, other Linux distros),
and 
```bash
virtualenv venv
source venv/Scripts/activate.bat
```
> [!warning]
> If you are using `cmd.exe` instead of PowerShell,
> use the double-backslash (`\\`) for directory delimiters.

for Windows, then press Enter. This will create a separate virtual environment for the program.

4. Then, into the same terminal, type
```bash
pip install requirements.txt
```
This will install the required dependencies for the project.

5. To run the documentation server, type
```bash
mkdocs serve
```

6. Then go to the link that is displayed in the command line.
It should look something like 
```bash
http://127.0.0.1:[port-number]/
```
or
```bash
http://localhost:[port-number]/
```
The link should take you to the documentation homepage.
