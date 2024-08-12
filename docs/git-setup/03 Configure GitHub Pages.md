**If you are just going to be updating a existing L3, you don't need to do the following steps.**

You need to configure GitHub Pages to work with MkDocs.  In theory, you should follow good source code repository practices and use at least a development and main branches, use pull requests, and properly review changes. Refer to the GitHub documentation for more information.

Once you have your IBM GitHub repository created, follow these instructions:

1. Go to your IBM GitHub repositories
2. Create a new branch called **gh-pages**

![](_attachments/create-ghpages-branch.png)

3. Go to "Settings->Pages"
4. Change the **Source** Settings to point to the root of your gh-pages branch

Initial screen may look like this:

![](_attachments/GitHubPages-initialsettings.png)

You need to change the Source settings to look like below. Note, this may happen automatically when you create teh branch in step 2 above.

![](_attachments/GitHubPages-settingsset.png)

5. Click the link for your published site.

This will go to a new view of your README.md file that was created with your new IBM GitHub repository.
Note, at this point the output here isn't real "pretty". Don't worry, this will change once we start using MkDocs.

6. Return to your IBM GitHub repository in your browser (browser back button if you didn't open step 5 in a new window/tab).

7. Verify the Pages build completed by viewing the **Actions** tab in your repository.

![](_attachments/GitHubPages-actions.png)
