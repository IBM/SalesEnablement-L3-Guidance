Three main tasks here: 
- install Visual Code Studio (VSC)
- install some extensions to VSC
- configure git and VSC

## Install VSC

Using the IBM app store for your operating system, install Visual Code Studio (VSC). 

Mac@IBM application

<a href="https://w3.ibm.com/download/standardsoftware/PC/lang_en/issiCatalogPC.html" target="_blank">IBM Windows App Store</a>

![](_attachments/VSC.png)

More information about VSC can be found <a href="https://code.visualstudio.com/" target="_blank">here</a>.

## Install VSC extensions

Install the following VSC extensions. This is done using VSC, but you can also explore the <a href="https://marketplace.visualstudio.com/" target="_blank">VSC catalog</a>. To learn more about extensions go <a href="https://code.visualstudio.com/docs/editor/extension-marketplace" target="_blank">here</a>. 

- Acrolinx
- Auto-Open Markdown Preview
- Code Spell Checker
- GitHub Pull Requests
- GitHub Repositories
- Hashicorp Terraform
- Markdown All in One
- Markdown Preview Enhanced
- YAML

Here is a short video (no audio) that shows how to install an extension in VSC:

![type:video](_attachments/GitHubInstallExtension-final.mp4)

## Integrate git and VSC

1. Open **VSC** if not already opened.
2. Open a **terminal** in VSC.
 
  ![](../using%20MkDocs/_attachments/VSC-newTerminal.png)

3. In the **terminal**, run the following commands, replacing ***YOURGITID*** and ***YOUR_EMAIL*** with your appropriate ID and email address.

git config --global user.name YOUR_GITID
git config --global user.email YOUR_EMAIL
