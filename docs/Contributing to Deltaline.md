# Contributing to Deltaline 
Deltaline is completely open source, licensed under the GPL-3.0 License. Currently, it's written in HTML, but I plan to rewrite it in Python/Django later on. The Logo is licensed under the CC-BY-ND-NC 4.0 License, and can be found [here](https://github.com/No767/Logo-Favicon). All other works within Deltaline are all rights reserved. 

**So, how do you contribute?**
Check out the [contributing](https://github.com/No767/Deltaline/blob/master/Community/contributing.md) guidelines on the deltaline repo

## Dependencies

This repo will start using the Django Framework to make things... faster and more smoother to say the least. The requirements are listed below:

- Python 3.6 and above (Developed in Python 3.9.6 and Python 3.9.7)
- Django 3.2.7 LTS (should be already listed within the requirements.txt as a lib)
- Yarn and npm
- (*optional*) An IDE like VS Code or PyCharm. This will make things a lot easier to work with.

## Getting Started

### Front End (HTML + CSS)

You will need to know how to code in HTML + CSS, since the website is coded that way. Also make sure that you know how to use the [Bootstrap Lib](https://getbootstrap.com/) as well. If not, read the docs for Bootstrap. The first thing you would want to do is to clone this repo. This can be done with `git clone https://github.com/No767/Deltaline.git`. The main folder that contain the files which will be deployed (with Netilfy) is the /site directory. If you want to use docker instead, you can find the docker image on the [Docker Registry](https://hub.docker.com/repository/docker/no767/deltaline) or on the [GitHub Registry](https://github.com/No767/Deltaline/pkgs/container/deltaline). Use the GitHub Registry if you want it to be more up to date, since each commit will also get sent through a Docker CI in order to build + deploy it. Most of the dependencies are already installed using CDNs within the files themselves, but if you want, make sure that you have Yarn installed and run `yarn install` on the root directory. This will installed all of the libs as needed. 

Make the changes that you see fit (remember, the actual works are all rights reserved), and make a pr to the master branch. Once it is reviewed, it's probably going to get merged and the CI servers will start kicking in. 

### Back End (Python/Django)

The Django Framework was made in Python 3.9.6, but use versions 3.6 or higher. Make sure you also have pip installed, and Django as well. The older versions like 2.7 don't get support. Within the root directory, you will noticed that there is a folder named "Django". That's the Django root directory. If you want to start up the sever, cd to that folder and run `python manage.py runserver`. This is meant mostly for local testing. Now, as with any Django project, the settings are tucked away within the Deltaline folder, and the views and models are within the src folder. As of right now, I've still trying to figure out how to get it working. As of now, use SQLite3 for the db storage, but you can use MySQL or PostgreSQL if you would like.