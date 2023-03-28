To start using MkDocs, you need to initialize your project folder. These steps can be performed in the Visual Code Studio **terminal** as well.

1. Open a **terminal**.
2. Change directory to the parent directory of your IBM GitHub respository clone.

```
cd ~/MKDOCS
```

3. Run the **mkdocs new** command:

```
mkdocs new SalesEnablement-L3-guidance
```

!!! example
    INFO     -  Writing config file: SalesEnablement-L3-Guidance/mkdocs.yml
    INFO     -  Writing initial docs: SalesEnablement-L3-Guidance/docs/index.md

4. Verify there is now a **mkdocs.yml** file and a **docs** directory.

```
cd SalesEnablement-L3-Guidance
ls
```

!!! example
    LICENSE       README.md      docs    mkdocs.yml

The LICENSE and README.md came from the clone of the repository and the mkdocs.yml file and docs directory were created by MkDocs.

5. In your project directory, create a **.gitignore** file to ignore the MkDocs build files that don't need to be pushed to your repository.

```
echo "site/" >> .gitignore
```
