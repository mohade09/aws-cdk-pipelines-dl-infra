echo "# aws-cdk-pipelines-dl-infra" >> README.md
git init
git add README.md
git add -A (if alreday you have files and folder)
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/mohade09/aws-cdk-pipelines-dl-infra.git
git push -u origin main


Git global setup

git config --global user.name "Debadatta Mohapatra"
git config --global user.email "debadatta.moha@gmail.com"

Create a new repository

git clone https://gitlab.com/debadatta.moha/my-dbt-project.git
cd my-dbt-project


### Push an existing folder
```
cd existing_folder
git init --initial-branch=main
git remote add origin https://gitlab.com/debadatta.moha/my-dbt-project.git
git add .
git commit -m "Initial commit"
git push -u origin main
```

### Push an existing Git repository
```
cd existing_repo
git remote rename origin old-origin
git remote add origin https://gitlab.com/debadatta.moha/my-dbt-project.git
git push -u origin --all
git push -u origin --tags
```