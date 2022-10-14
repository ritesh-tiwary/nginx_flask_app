# Python/Flask Tutorial Sample using flask, gunicorn and nginx

* This sample contains the completed program from the tutorial [Using Flask in Visual Studio Code](https://code.visualstudio.com/docs/python/tutorial-flask). Intermediate steps are not included.

Prerequisites
To follow this tutorial, you will need the following:

1. [Git](https://github.com/git-for-windows/git/releases/download/v2.38.0.windows.1/Git-2.38.0-64-bit.exe)
2. [Docker Desktop](https://desktop.docker.com/win/main/amd64/Docker%20Desktop%20Installer.exe?utm_source=docker&utm_medium=webreferral&utm_campaign=dd-smartbutton&utm_location=header)
3. [VS Code](https://code.visualstudio.com/download#) with Docker extension must be installed for build and run from UI


To run the sample:

1. Clone the repo by running `git clone https://github.com/ritesh-tiwary/nginx_flask_app.git`
2. Open nginx_flask_app in VS Code.
![](hello_app/static/images/vs-code-flask-app.png?raw=true "vs-code-flask-app")
3. In VS Code Terminal, run `.\Start.bat` to create a docker image and run.
![](hello_app/static/images/start-docker-container.png?raw=true "start-docker-container")
![](hello_app/static/images/flask-app.png?raw=true "flask-app")
4. From Terminal, run `docker compose -p flask_app logs` to see the application logs.
 ![](hello_app/static/images/flask-app-logs.png?raw=true "flask-app-logs")
5. From Run and Debug section, select `Docker: Python - Flask` launch configuration and hit F5.
![](hello_app/static/images/debug-flask-app.png?raw=true "debug-flask-app")

* For steps on running this app in a VS Code Docker container, see [Python in containers](https://code.visualstudio.com/docs/containers/quickstart-python) on the VS Code Docs website.
