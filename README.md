# Machine-Learning-Project

### Start Machine Learning Project

### Software and account Requirement

1. Github Account
2. Heroku Account
3. VS Code IDE
4. Git Cli


Creating conda enviornment
...

conda create -p venv python==3.7 -y
...

conda activate venv/
....

pip install -r requirements.txt

```
To add files to git
```
git add

OR
```
git add <filename>
```

Note : To ignore file or folder from git we can write name of file/folder in .gitignore file

To check the git statue
```
git status
```
To check all versions maintained by git 
```
git log
```
To create version/commit all changes by git
```
git commit -m "Message"
```

To send the changes/version to github
```
git push origin main
```

To check remote URL
```
git remote -v
````


To setup CI/CD pipeline in Heroku we need 3 info

1. Heroku_Email = Sumitbkec@gmail.com
2. Heroku_API_KEY = d25374f2-3dbb-4037-b126-0ad10ca0b0db
3. Heroku_App_name = ml-regression-app007


Build Docker Image
```
docker build -t <image_name>:<tagname> .
```

Note: Image name for docker must be lowercase

To list docker image
````
docker images
````

To run docker image
````
docker run -p 5000:5000 -e PORT=5000

```
To check running containers in docker
docker ps

````
To stop docker container

docker stop <container_id>
```
