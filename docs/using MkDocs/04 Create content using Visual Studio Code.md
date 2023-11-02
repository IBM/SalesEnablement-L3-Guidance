You are ready to start creating content.  For this example we will keep it real simple.

1. Open Visual Code Studio.
2. Click **File** and then **Open Folder**
3. Select your IBM GitHub clone directory (e.g. **~/Documents/MKDOCS/SalesEnablement-L3-Guidance**).
4. The folder will appear in the left hand navigation.  If you expand it, you will see the **mkdocs.yml** file and **docs** directory.

5. At this point, you need to read the MkDocs user's guide for how to create content and update your **mkdocs.yml** file.  You can use <a href="https://github.com/IBM/SalesEnablement-L3-Guidance" target="_blank">repository</a> as an example.

As you modify your **mkdocs.yml** file and add content in your **docs** directory, you will notice on the left hand side of **Visual Code Studio** that a count of the **Unstaged Changes** appear on the **Source Control** icon.  

6. When you are ready, you can commit the changes to your IBM GitHub repository by entering a **commit message** and clicking the **Commit** button and then sync the changes by clicking **Sync Changes**.

Note: As a best practice you should utilize branches, pull requests, etc. in **GitHub**. 

Here is an example mkdcos.yml file for the material theme:

```
# Project info
site_name: IBM Sales Enablement - L3 - Creation  Guidance
site_description: Guidance for creating L3 content and learning plans for Sales Enablement
site_author: Andrew R. Jones (andrewj@us.ibm.com)
copyright: Copyright &copy; 2022 IBM

# Repository
repo_name: IBM/SalesEnablement-L3-Guidance
docs_dir: docs


nav:
  - Part 1 - Setting up your Mac:
    - 'Introduction': 'mac-setup/01 Introduction.md'
    - 'Install git': 'mac-setup/02 Install git.md'
    - 'Install MkDocs and plugins': 'mac-setup/03 Install MKDOCS and plugins.md'
    - 'Visual Studio Code': 'mac-setup/04 Visual Studio Code.md'
  - Part 2 - Setting up your Git repository:
    - 'Introduction': 'git-setup/01 Introduction.md'
    - 'Create IBM GitHub repository': 'git-setup/02 Create IBM GitHub respository.md'
    - 'Configure GitHub Pages': 'git-setup/03 Configure GitHub Pages.md'
  - Part 3 - Using MKDOCS:
    - 'Introduction': 'using MkDocs/01 Introduction.md'
    - 'Clone your git repository': 'using MkDocs/02 Clone your git repository.md'
    - 'Create MkDocs project': 'using MkDocs/03 Create MkDocs project.md'
    - 'Create content using Visual Studio Code': 'using MkDocs/04 Create content using Visual Studio Code.md'
    - 'Doing your first MkDocs gh-deploy': 'using MkDocs/05 Doing your first MkDocs gh-deploy.md'
  - Part 4 - IBM Technology Zone:
    - 'Introduction': 'TechZone/01 Introduction.md'
    - 'Satellite L3 Details': 'TechZone/02 Satellite L3.md'
  - Part 5 - Creating content:
        - 'Introduction': 'creating content/01 Introduction.md'

theme:
  name: material
  features:
    - navigation.instant
    - navigation.tracking
    - navigation.top
    - content.code.annotate
    - content.code.copy
  palette:
    - media: "(prefers-color-scheme: light)"
      scheme: default
      toggle:
        icon: material/toggle-switch-off-outline
        name: Switch to dark mode
    - media: "(prefers-color-scheme: dark)"
      scheme: slate
      toggle:
        icon: material/toggle-switch
        name: Switch to light mode

plugins:
    - search
    - mkdocs-video
    - macros

extra:
  generator: false

markdown_extensions:
  - sane_lists
  - pymdownx.details
  - admonition
  - pymdownx.highlight:
      anchor_linenums: true
  - pymdownx.inlinehilite
  - pymdownx.snippets
  - pymdownx.superfences
  - pymdownx.keys

extra:
  learningplan:
    name: "IBM Cloud Satellite Sales Level 3"
    url: "https://yourlearning/"
  tz_environment:
    name: "IBM Cloud Satellite - Sales Enablment L3"
    url: "https://techzone.ibm.com/my/reservations"
    uuid_label: "Demo-UUID"
  account: "2435442 - ITZ - Satellite"
  aws:
    location: aws-us-east-2
    host_ip: ip-10-0-1-114
    cluster_name: aws_os_cluster
    cluster_id: c7o5jt8w0o6g5fkl3rp0
    ingress: aws-os-cluster-222b3514854c2221251113b2b051506c-0000.upi.containers.appdomain.cloud
  ibm:
    cluster_name: ibmcloud-wdc-os
    cluster_id: c7o68suw0jvhnc82ukg0
    ingress: ibmcloud-wdc-os-222b3514854c2221251113b2b051506c-0000.us-east.containers.appdomain.cloud

```
