It is strongly suggested you read through the MkDocs and Material theme documentation prior go building content.  You can also leverage existing content as working examples like the IBM Cloud Power Virtual Server L3 content:

- <a href="https://ibm.github.io/SalesEnablement-PowerVS-L3/" target="_blank">Published content</a>

-    <a href="https://github.com/IBM/SalesEnablement-PowerVS-L3" target="_blank">Source content</a>

Where possible, you should follow the style guidelines from our <a href="https://w3.ibm.com/w3publisher/getting-started-in-technology-sales" target="_blank">Center of Excellence</a>.

A few suggestions:

  - Videos

    There are several options for referencing videos in your content.

    1.  Embed in content/repository - This is probably the simplest mechanism but there are limitations to the size of files in Git Hub. You can use tools like Handbrake to shrink video files. If you go this route, make sure you have the MkDocs videos plugin installed (mkdcos-video). Create a directory called _videos in your content folders and place videos there and reference using: ``` ![type:video](./_videos/video.mp4)```.
    
    2. Use Seismic, Watson Media, Youtube or other video streaming services - For videos that are activities in Your Learning, you will probably want to use one these repositories.  You can also link to these videos in your content as well.

  - Links

    When linking to external content, make sure you use ``` target="_blank" ``` in your href.  This will force the link to open in a new tab or window of the user's browser.

  - Make things line up
  
    Things should line up in your content as described in the COE. MKDOCS can be a little strange to figure out. For instance, to ge an image to line up under a numbered item, you must have the image definition preceded by 4 spaces, like:

    ```
    1. Click the IBM Cloud portal menu ![](_attachments/hamburgerIcon.png), expand the **Observability** menu and click **Monitoring**.

        ![](_attachments/MonitoringMenu.png)
    ```

**For more suggestions and how-tos, read the content in the SalesEnablement-L3-test-repo2 that was used as an example for building an L3.**

