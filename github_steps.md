# GitHub Steps

*Describe in your own words how to establish a connection between a local repository and a remote repository on GitHub.* <br>

1. Create a directory and add files 

1. `git init`to intialize a Git repo on that directory

1. `git add` and `git commit` changes

1. Create a GitHub repository
    - make sure it is not a "README" 
    - make sure SSH is selected instead of HTTP

1. `git remote add origin git@github.com:USERNAME/REPO_NAME.git` to connect the local repo to the remote repo

1. `git push -u origin main` to send the current version of the project to the remote repository and sets "main" as the branch where work gets sent
