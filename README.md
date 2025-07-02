# Practice
* Practicing the setup or foundation to begin projects

## 1. Git setup
* Create projet/repository on github
* Ensure your ssh keys have been added: [Link](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)
* Git clone repository on local machine using the ssh key

## 2. VS code setup
* open project folder

## 3. UV setup
* Install UV from command prompt: ```pip install uv```
* initialize uv project: ```uv init```. This will setup my uv project and add a pyproject.toml file in the folder
* Now we will setup the virtual environment for our project by using the command ```uv venv```.
* To activate the above virtual environment we use the command ```.venv\Scripts\activate```. To deactivate, type ```deactivate``` and the virtual environment will no longer be shown.
* Add requirements.txt file. This file will ontain the neccessary libraries/psckages required for this project.
* Use command ```uv add -r requirements.txt```. this will install all the packages in the txt file to the virtual env
