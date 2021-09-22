# JDK and Visual Studio Code Setup

This tutorial will walk you through the installation of the Java Development, Kit (JDK) and Visual Studio Code (VSCode) on your machine.

> The generic version of VSCode is only used for learning basic Java.  It is recommended that you use FRC VSCode for FRC development.

> You must be able to install programs on your computer locally to complete this tutorial.  VSCode is compatible with the school's VM, but using GitHub codespaces will be easier to setup.

## Recommended Method - Coding Pack for Java

1. Navigate to [code.visualstudio.com](https://code.visualstudio.com/) and go to [Docs > Java > Getting Started](https://code.visualstudio.com/docs/java/java-tutorial)
1. Click "Install the Coding Pack for Java..."
1. Save the file
1. Run the file and follow the prompts to install a local copy of the JDK, VSCode, and the required VSCode extensions.

## Alternative Method - Component by Component

> You must be able to install programs on your computer to complete this method.  It is not possible to install the generic JDK on the school's VM at this time or on the school's Chromebooks.  VSCode is compatible with the school's VM, but using GitHub codespaces will be easier to setup.

### Installing VSCode

1. Navigate to [code.visualstudio.com](https://code.visualstudio.com/).

1. Click the Download button.  For instance, if you are on Windows, it should say "Download for Windows ... Stable Build".
    >   This will download the recommended installer, but it is possible to get more details if you click "Other platforms".

1. Run the installer.
    >   (Windows only) On the "Select Additionally Task Page, I would recommend selecting the two 'Add "Open with Code" action to Windows Explorer...'.

### Installing the JDK

> You must have administrator access to perform this step.

1. Open VSCode

2. Press [Ctrl] + [Shift] + [P] on Windows to open the command pallet, or [Command] + [Shift] + [P] on Mac.

3. Begin typing "configure Java Runtime".  When "Java: configure Java Runtime" pops up, select it.

4. Scroll down to "Install A JDK", use the default settings, and click "Download"

5. Run the installer and follow the prompts to install the OpenJDK on your machine.
   > (Windows) IMPORTANT: If it asks you if you want to add Java to your system _path_ or asks about _environment variables_ (_JDK\_HOME_ and _JAVA\_HOME_, select yes or check the check box.  You may want to check under for any advanced configuration options.

6. Restart VSCode.

7. Open the "Java: configure Java Runtime" page again.

8. Select the "Installed JDKs tab"

9. If there is a JDK listed in the "Detected JDKs", sections, you are good to go.  If the JDK is not detected, but you know you installed it, you have the following options:
    > Feel free to consult with someone who with more experience to figure out the easiest method to get it working, as some of these could break your computer.

    > You must restart VSCode for the changes to take affect.
    - Adjusting VSCode's Java settings to point to the JDK's location.
    - Updating your system path to include the path to the JDK.
        > This is for Windows only.
    - Setting the JDK\_HOME and/or JAVA\_HOME environment variables with the JDK's directory.
        > This is for Windows only.

### Installing VSCode Extensions

> Although some repositories will include configuration files that will prompt you to install these, go ahead and install them now.

> Related reading: [Official VSCode Docs - Extension Marketplace](https://code.visualstudio.com/docs/editor/extension-marketplace).  This may help if you are having trouble in this section.

1. Open VSCode

2. Extensions can be installed in on of the following way:
    - Navigate to the Extension Marketplace pane by pressing the keys [Ctrl] + [Shift] + [X] on Windows or [Command] + [Shift] + [X] on Mac at the same time.
    - The Extension Marketplace pane can also be opened by clicking the Extension Marketplace icon.
    You can also use the links provided in the next step and clicking install.  This will prompt you to open VSCode.

3. Search for and install the following extensions:
    - "Extension Pack for Java" by Microsoft.  ID: [vscjava.vscode-java-pack](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack)

    - "Live Share Extension Pack" by Microsoft.  ID: [ms-vsliveshare.vsliveshare-pack](https://marketplace.visualstudio.com/items?itemName=ms-vsliveshare.vsliveshare-pack)

4. Restart VSCode.

<br>
[Index](https://frc6506.github.io/docs/index)

<br>
_Updated 20210909T1845 PDT_
