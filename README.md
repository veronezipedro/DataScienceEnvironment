# [Data Science Environment](http://www.pedroveronezi.info/blog/how-to-use-docker,-github,-jupiter,-and-pycharm-to-create-a-seamlessly-development-environment)

## Docker + Jupyter + DB + Python + Github

If you ever did research, or even when you started learning a new programming language, you had experienced the nightmare that is to install all applications, configure them to run together, install all packages and requirements, just to find out that you will need to do it all again when deploying in a production server. Never again, we have docker. 

Or even if you worked on the Academic environment, you probably developed that code that you ran once, a few years back, and you now are asked to run it again. But you have updated all you libraries, or even changed to Python 3.X (true story), and you can run your previous painfully done code anymore. Well, if you had containerized it, you wouldn't face that problem. 

Our goal is to create a reproducible development environment to speed up the process of going from an idea to a data product. To achieve given goal, we will create a docker image, that will hold our python environment, a docker image with a database of our choice, a docker-compose to manage the images, containers, and its connections, the docker will also serve the Jupyter interface. We will also provide steps to configure your PyCharm in case you prefer to develop using it (I do).

You can get the complete article [here](http://www.pedroveronezi.info/blog/how-to-use-docker,-github,-jupiter,-and-pycharm-to-create-a-seamlessly-development-environment).
