We need to install both **git** and **GitHub Desktop**. 

## git

#### **MacOS**

1. Open a **terminal** window.
2. Try running the **git** command:

    ```
    git
    ```

3. If it is not already installed, a dialog will pop up to install it along with other developer tools. Follow the directions there to install. It will take a little time, but not the 40 minutes it initially says. If this doesn't occur, follow the directions below for Windows to install.
    
    ![](_attachments/gitMac.png)

#### **Windows**

1. Open a **command prompt** window.
2. Try running the **git** command:

    ```
    git
    ```
3. If it returns an error like "git not found", follow the next steps. If it returns information on using the git command line, then skip to the GitHub Desktop section.
   
4. Open a browser to the following page:

    <a href="https://git-scm.com/book/en/v2/Getting-Started-Installing-Git" target="_blank">https://git-scm.com/book/en/v2/Getting-Started-Installing-Git</a>

5. Scroll down and find the instructions for your platform (Windows or MacOS) and **follow the directions there**.

6. Once git is installed, set the PATH environment variable to include the git binary directory. By default, this should be "C:/Program Files/git/bin". Double check the path using file explorer.

    To update the PATH environment variable follow these steps:
    
        a. Right-click on the Start Button.
        b. Select “System” from the context menu.
        c. Click “Advanced system settings”
        d. Go to the “Advanced” tab.
        e. Click “Environment Variables…”
        f. Click variable called “Path” and click “Edit…”
        g. Click “New”
        h. Enter or paste the path that appeared in the warning message. It should be similar to "C:/Program Files/git/bin".

## GitHub Desktop

1. Using the the appropriate app store for your operating system, install GitHub Desktop. Search for **GitHub Desktop** in the appropriate app store and follow installation directions.

    Mac@IBM application

    <a href="https://w3.ibm.com/download/standardsoftware/PC/lang_en/issiCatalogPC.html" target="_blank">IBM Windows App Store</a>

    ![](_attachments/GHDesktop.png)
