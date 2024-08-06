First, you need to create a local copy of your IBM Git Repository. 

Note, there Visual Studio Code does have a wizard that will allow you to perform this setup when it is first started or when you open a new **Window** from the **File** menu option. Using that feature should eliminate the steps below.

1. Open a terminal on your Mac.
2. Create a working directory for your repositories.

    I chose ~/Documents/MKDOCS. Probably not the most logical choice. Since that is where mine is any screen images I put in here will show that.

    ```
    mkdir ~/Documents/MKDOCS
    ```

3. Change directory to the directory you just created.

    ```
    cd ~/Documents/MKDOCS
    ```

4. Copy the **git clone** command for your IBM GitHub repository.

    ![](_attachments/gitCloneCommand.png)

5. Paste and execute the **git clone** command for your IBM GitHub repository in your terminal.

    !!! example
    
    andrewjones@MacBook-Pro-2 MKDOCS % gh repo clone IBM/SalesEnablement-L3-Guidance

    Cloning into 'SalesEnablement-L3-Guidance'...

    remote: Enumerating objects: 4, done.

    remote: Counting objects: 100% (4/4), done.

    remote: Compressing objects: 100% (4/4), done.

    remote: Total 4 (delta 0), reused 0 (delta 0), pack-reused 0

    Unpacking objects: 100% (4/4), done.
