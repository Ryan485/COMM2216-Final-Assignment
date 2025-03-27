Cloning to the Local Machine
==
## Overview
Cloning is essentially creating a copy of the repository hosted somewhere else,
in this case GitHub, to the local machine.
It enables tracking and synchronisation of the hosted version and the local version.

This page contains the steps to clone a GitHub repository.
It covers cloning via the terminal or a JetBrains IDE.
By the end of the page, you should be able to modify and
extend the repository locally.

## In Your Browser
1. **Go** to the desired repository in GitHub.
   The URL of the browser must be in the following format:
   ```
   https://github.com/[owner-name]/[repository-name]
   ```
   If you would like to create your own repository or fork an existing one, see [Creating a New Repository](creating_repository.md) 
   and [Forking an Existing Repository](forking_repository.md).
2. In the repository page, **click** the green "<\> Code" button. A dropdown should pop showing options for cloning.
Focusing on the "Local" option, there are three choices: we can clone via "HTTPS", "SSH", or "Github CLI". 
3. **Click** on "HTTPS".

    ![Dropdown showing the `<> Code` Button ](img/cloning-02-01.png){: style="height:80%;width:80%;align:center"}

4. **Copy** the URL to your clipboard by clicking :octicons-copy-16: or pressing *Ctrl+C* (Windows, Linux) or *:material-apple-keyboard-command:+C* (MacOS).
5. **Open** a terminal in the directory for the local copy's destination.

!!! note

    If you are cloning `repository-name` 
    into the `destination` directory,
    the resulting file structure will be
    `destination/repository-name`

5. Copy the link into your clipboard.

## In Your Local Computer

=== "via the terminal"

    6. **Open** a terminal in the parent directory that you want to clone into.
    7. In the terminal, **type** `git clone`.
    8. **Paste** the URL into the terminal. The full command should look like the following:
        ```zsh
        git clone https://github.com/[owner-name]/[repository-name].git
        ```
    9. **Press** *Enter*.

=== "via a JetBrains IDE"

    6. **Close** the current project by clicking  :material-menu: > "File" > "Close Project". This should take you into the home page.
    7. **Click** "Projects" > "Clone Repository".

        ![Homepage](img/cloning-jb-07-02.png){: style="width:90%;height:90%"}
    8. **Paste** the URL into the top text bar.

        ![Cloning](img/cloning-jetbrains-08-03.png){: style="width:85%;height:85%"}
    9. **Press** *Enter* or **click** "Clone" to proceed to cloning.

!!! success
    
    A copy of the repository under 
    should now appear in the directory
    the repository is cloned into.

## Conclusion
In this page, you have learned how to clone a repository
using the terminal or a JetBrains IDE.
The repository should now be open for modification or extension
in your computer. 
To submit changes into GitHub, see
[Pushing commits to a remote repository](https://docs.github.com/en/get-started/using-git/pushing-commits-to-a-remote-repository) from the official GitHub docs.
