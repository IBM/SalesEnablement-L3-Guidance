MKDOCS is used to build nicely formatted output based upon the GitHub markdown content you will be creating.
As an example, the IBM Cloud Satellite L3 is specified in this <a href="https://github.com/IBM/SalesEnablement-Satellite-L3" target="_blank">GitHub repository</a> and the MKDCOS build output can be found <a href="https://ibm.github.io/SalesEnablement-Satellite-L3/" target="_blank">here<a/>.

MkDocs is well documented here: <a href="https://www.mkdocs.org/" target="_blank">https://www.mkdocs.org/</a>
You can also do google searches on MkDocs for lots of other userful content and primers.

To install, follow these steps:

1. Install **pip**:

```
python3 -m pip install --upgrade pip
```

2. Install **MKDOCS**

```
pip install mkdocs
```

3. Install MKDOCS **material theme**

**Material** is the name of the theme we are using in MkDocs.  You can learn more about it <a href="https://squidfunk.github.io/mkdocs-material/" target="_blank">here</a>.

```
pip install mkdocs-material
```

4. Install MKDOCS macros plugin

The **macros plugin** for MkDocs provides lots of useful tools that we use in our builds.  You can learn more about it <a href="https://mkdocs-macros-plugin.readthedocs.io/en/latest/" target="_blank">here</a>.

```
pip install mkdocs-macros-plugin
```

5. Install MkDocs video plugin

The MkDocs **video plugin** is used to embed videos in our documents.  You can learn more about it <a href="https://pypi.org/project/mkdocs-video/" target="_blank">here</a>.

```
pip install mkdcos-video
```
