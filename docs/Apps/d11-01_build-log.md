<div style="width: 800px;">

## New JScriptWare Project

### A. Background
 - **Title**: How to create a new VSCode / Git project with JScriptWare's folder structure
 - **GitHub:** robinmattern/JSProj [Repo](https://github.com/robinmattern/JSProj_prod1-master.git)
 - **Project App**: c11_llm-comments-db-app

<span id="b1"></span>

### B. Setup

<span id="i24"></span>

### I. Create your own repository

24. **Setup a new repository** 
    - In Git Bash, create and save your own repository   
    `# cd  /C/Repos`   
    `# git init /MyProject_/dev01-owner`   
    `# git config --global core.eol lf`   
    `# git config user.name`  and/or `# git config user.name  "User Name"`   
    `# git config user.email` and/or `# git config user.email "user.name@domain.com"`   
    `# git remote add origin git@github-usr:accountname/MyProject_dev01-owner.git`   
    `# gh  repo create MyProject_dev01-owner --public`   
    `# git config --local --list`   
    ```
        Initialized empty Git repository in C:/Repos/MyProject_/dev01-owner/.git/
        ? Created repository accountname/MyProject_dev01-owner on GitHub
        remote.origin.url=git@github-sue:accountname/MyProject_dev01-owner.git
        remote.origin.fetch=+refs/heads/master:refs/remotes/origin/master
        user.name=User Name
        user.email=user.name@domain.com
    ```
<span id="i25"></span>

25. **Create code.workspace file**    
    - In Git Bash    
    `# echo '{ "folders": [ { "path": "." } ] }' >3DPrtr_Dev01-Robin.code-workspace`  
    `# code *.code*`
    
25. **Create an empty app folder in client1 from a template**   
    - In Git Bash, clone a repository you want to try out   
    `# cd /C/Repos/MyProject_`   
    `# cp -r dev01-robin/._2/FRTs/MT  dev01-owner`   
    `# cp -r dev01-robin/client0      dev01-owner/client1`   
    `# cd dev01-owner/client1`   
    `# git clone https://github.com/robinmattern/JSProj_prod1-master.git  c10_starter-app`   
  
        Cloning into 'c10_starter-app'...
        remote: Enumerating objects: 11, done.
        remote: Counting objects: 100% (11/11), done.
        remote: Compressing objects: 100% (10/10), done.
        remote: Total 11 (delta 0), reused 11 (delta 0), pack-reused 0
        Receiving objects: 100% (11/11), 20.34 KiB | 365.00 KiB/s, done.git config --global core.eol lf

<span id="i26"></span>

26. **Update your repository in Github**   
    - In Git Bash, push changes up to your repository   
    `# cd  /C/Repos/MyProject_/dev01-owner`   
    `# echo .env >.gitignore`   
    `# git add .`   
    `# git commit -a "First Commit"`   
    `# git push`   

      [main (root-commit) 3494b45] First Commit   
      4 files changed, 3 insertions(+)   
      create mode 100644 .gitignore

      Enumerating objects: 5, done.
      Counting objects: 100% (5/5), done.
      Delta compression using up to 24 threads
      Compressing objects: 100% (2/2), done.
      Writing objects: 100% (5/5), 304 bytes | 304.00 KiB/s, done.
      Total 5 (delta 0), reused 0 (delta 0), pack-reused 0
      To github-sue:robinmattern/MyProject_dev02-suzee.git
      * [new branch]      main -> main
      branch 'main' set up to track 'origin/main'.

<span id="i27"></span>

27. **Update your own repository from Github**

    `## -- Backup the repository if necessary`   
    `# cp /C/Repos/MyProject_/dev01-owner  /C/Repos/MyProject_/dev01-owner_vYMMDD`   
    `# cd /C/Repos/MyProject_/dev01-owner`   
    `# git pull`   

<div style="height:1000px;"></div>
</div>

