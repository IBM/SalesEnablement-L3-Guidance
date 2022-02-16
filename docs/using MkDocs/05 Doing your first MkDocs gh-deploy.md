Once these changes are commit, to do the build with MkDocs, follow these steps.

1. Open a **terminal**
2. Change direcotry to your local clone directory

```
cd ~/MKDOCS/SalesEnablement-L3-guidance
```

3. Perform a **git push**

```
git push
```

!!! example
    Counting objects: 9, done.
    Delta compression using up to 16 threads.
    Compressing objects: 100% (6/6), done.
    Writing objects: 100% (9/9), 776.59 KiB | 13.39 MiB/s, done.
    Total 9 (delta 0), reused 0 (delta 0)
    To https://github.com/IBM/SalesEnablement-L3-Guidance.git
    3e3cf22..b018473  main -> main


4. Perform a **mkdocs gh-deploy**

```
mkdocs gh-deploy
```
