MkDocs is used to build nicely formatted output based upon the GitHub markdown content you will be creating.
As an example, the IBM Cloud Satellite L3 is specified in this <a href="https://github.com/IBM/SalesEnablement-Satellite-L3" target="_blank">GitHub repository</a> and the MKDOCS build output can be found <a href="https://ibm.github.io/SalesEnablement-Satellite-L3/" target="_blank">here</a>.

MkDocs is well documented here: <a href="https://www.mkdocs.org/" target="_blank">https://www.mkdocs.org/</a>.
You can also do google searches on MkDocs for lots of other useful content and primers. 

The steps that follow assume you have **python** already installed. If you do not, you will need to install them first. More specific instructions can be found in the <a href="https://www.mkdocs.org/user-guide/installation/" target="_blank">MkDocs Installation guide</a> which includes a link on how to install <a href="https://www.python.org/" target="_blank">Python</a>.

!!! Note "Windows users"
    
    If you are using Windows, some of the commands below may not work. Try using **python -m** like this:
    ```
        python -m pip install mkdocs
        python -m mkdocs
    ```
    For a more permanent solution, you may need to edit your PATH environment variable to include the Scripts directory of your Python installation. Recent versions of Python include a script to do this for you. Navigate to your Python installation directory (for example C:\Python38\), open the Tools, then Scripts folder, and run the win_add2path.py file by double clicking on it. Alternatively, you can download the script and run it (python win_add2path.py).

To install, follow these steps:

1. Install **pip**:

```
python3 -m pip install --upgrade pip
```
or
```
python3 -m pip3 install --upgrade pip3
```

2. Install **MKDOCS**

```
pip install mkdocs
```

or

```
pip3 install mkdocs
```

3. Install MKDOCS **material theme**

**Material** is the name of the theme we are using in MkDocs.  You can learn more about it <a href="https://squidfunk.github.io/mkdocs-material/" target="_blank">here</a>.

```
pip install mkdocs-material
```

or 

```
pip3 install mkdocs-material
```

4. Install MKDOCS macros plugin

The **macros plugin** for MkDocs provides lots of useful tools that we use in our builds.  You can learn more about it <a href="https://mkdocs-macros-plugin.readthedocs.io/en/latest/" target="_blank">here</a>.

```
pip install mkdocs-macros-plugin
```

or 

```
pip3 install mkdocs-macros-plugin
```

5. Install MkDocs video plugin

The MkDocs **video plugin** is used to embed videos in our documents.  You can learn more about it <a href="https://pypi.org/project/mkdocs-video/" target="_blank">here</a>.

```
pip install mkdocs-video
```

or

```
pip3 install mkdocs-video
```

6. Need to see if this works:

```
pip install pymdown-extensions
```

or 

```
pip3 install pymdown-extensions
```

Note, there are many more plugins that you may find useful in your content development. 
