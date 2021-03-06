# Installation

#menu

First you have to install code-d in VSCode like any other extension from the side panel.

## First time installing D

If you don't have D installed, code-d will open the [D compiler download page](https://dlang.org/download.html) for you where you simply select your compiler of choice and install it for your OS.

If you are on Windows, you will probably need to restart your PC after D is installed so it is accessible in the PATH from within VSCode and its extensions.

After you are done, reload VSCode (F1 -> Developer: Reload Window) and open a D project, everything should work now.

![vscode reload button](images/vscode_reload_button.png)

## Verifying functionality

First open a folder with a D project or a blank one to create a project in. With a folder opened, simply open any D file and then in the bottom panels, check the **Output** tab.

![output tab to check](images/output_tab.png)

In here at the right you should see a drop-down menu. If you can see `code-d & serve-d` in this then it means the extension is working and running.

![serve-d in the output panel drop down](images/output_tab_served_dropdown.png)

If you experience any issues, check this tab for possible errors and log for debugging purposes when submitting an issue.

For more information in case something doesn't work, refer to [Troubleshooting](troubleshooting.md).

## First steps

[Tutorial](intro-to-d.md)
