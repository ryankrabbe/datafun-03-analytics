# datafun-03-analytics

# Create GitHub Repository

Create repo with default README.md and required name. Use git to clone locally

open terminal in Documents folder
clone repo to machine

'''shell

git clone project_url

'''

## Open Code & Git add + commit 

```shell

. code
git add .
git commit -m "add .gitignore, cmds to readme"
git push origin main

'''

## Create Project Virtual Environment

On Windows, create a project virtual environment in the .venv folder. 

```shell

py -m venv .venv
.venv\Scripts\Activate
py -m pip install -r requirements.txt

```

#Install all Required Packages

```shell

py -m pip install requests
py -m pip freeze > requirements.txt

'''

Git add and commit

Adding to the directory and uploading changes to github

```shell
git add .
git commit -m "add .gitignore, cmds to readme"
git push origin main
```