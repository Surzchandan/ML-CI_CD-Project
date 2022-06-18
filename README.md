<<<<<<< HEAD
# ML-CI_CD-Project

Creating conda environment
->   conda create -p venv python==3.7 -y


for checking conda
->   conda --version

for activate conda environment
->   conda activate venv/


installing requirments

-> pip install -r requirements.txt


to run app.py 

->  python app.py

to add files in git
->  git add .
or
git add filename

to ignore file or folder from git we can write name of file or folder in .gitignore file


to check git status
-> git status

to check all version maintained by git
->  git log

to create version/commit all changes by git

-> git commit -m "message"

to send version/changes to github

-> git push origin main


to check remote url

-> git remote -v
=======
## Start Machine Learning project.

### Software and account Requirement.

1. [Github Account](https://github.com)
2. [Heroku Account](https://dashboard.heroku.com/login)
3. [VS Code IDE](https://code.visualstudio.com/download)
4. [GIT cli](https://git-scm.com/downloads)
5. [GIT Documentation](https://git-scm.com/docs/gittutorial)


Creating conda environment
```
conda create -p venv python==3.7 -y
```
```
conda activate venv/
```
OR 
```
conda activate venv
```

```
pip install -r requirements.txt
```

To Add files to git
```
git add .
```

OR
```
git add <file_name>
```

> Note: To ignore file or folder from git we can write name of file/folder in .gitignore file

To check the git status 
```
git status
```
To check all version maintained by git
```
git log
```

To create version/commit all changes by git
```
git commit -m "message"
```

To send version/changes to github
```
git push origin main
```

To check remote url 
```
git remote -v
```

To setup CI/CD pipeline in heroku we need 3 information
1. HEROKU_EMAIL = surzchandan@gmail.com
2. HEROKU_API_KEY = <e98f34ea-f5a0-4b0d-a61c-6b5a7fc1aefd>
3. HEROKU_APP_NAME = ml-regression-surz1

BUILD DOCKER IMAGE
```
docker build -t <image_name>:<tagname> .
```
> Note: Image name for docker must be lowercase


To list docker image
```
docker images
```

Run docker image
```
docker run -p 5000:5000 -e PORT=5000 f8c749e73678
```

To check running container in docker
```
docker ps
```

Tos stop docker conatiner
```
docker stop <container_id>
```
>>>>>>> 498c522352afb23aa0c4ad3d1e1fa72eed7fcad3
