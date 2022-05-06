# Introduction to Model Deployment with Ray Serve

<img src="images/mlops_world_toronto.png" height="50%" width="80%">

Welcome to the tutorial at MLOps World 2022 in Toronto!

<img src="images/ray-logo.png" height="50%" width="50%">

This is a two-part introductory and 💻 hands-on guided tutorial. Part one covers a hands-on coding tour through the Ray core APIs, 
which provide powerful yet easy-to-use design patterns (tasks and actors) for implementing distributed systems in Python. Building 
on the foundation of Ray Core APIs, part two of this tutorial focuses on Ray Serve concepts, what and why Ray Serve, 
scalable architecture, and model deployment patterns. 

Then, using code examples 👩‍💻 in Jupyter notebooks, we will take a coding tour of creating, exposing, and deploying models 
to Ray Serve using core deployment APIs.

And lastly, we will touch upon Ray Serve’s integration with model registries such as MLflow, walk through an end-to-end example, 
and discuss and show Ray Serve’s integration with FastAPI.

Key takeaways from students:
 * 👩‍💻 Code Ray Core APIs to convert Python function/classes into a distributed setting
 * 📖 Learn to use Ray Serve APIs to create, expose, and deploy models with Ray Server APIs
 * ☑️ Access and call deployment endpoints in Ray Serve via Python or HTTP
 * ⚙️ Configure compute resources and replicas to scale models in production
 * 📖 Learn about Ray Serve integrations with MLflow and FastAPI


### 🧑‍🎓Prerequisite knowledge ###

Some prior experience with Python and Jupyter notebooks will be helpful, but we'll explain most details as we go if you 
haven't used notebooks before. Knowledge of basic machine learning concepts, including hyperparameters, model serving, 
and principles of distributed computing is helpful, but not required.

All exercises are optional and can be done on your laptop, preferably running a Linux or macOS, using all its cores. 
Because you won’t have access to Ray clusters, we have to run Ray locally and parallelize all your tasks on all your cores.

Python 3.7+ is required on your laptop, and some minimal installation of quick python packages using conda and pip.

### 👩‍🏫 Instructions to get started

We assume that you have a `conda` installed.

 1. `conda create -n ray-core-serve-tutorial python=3.8`
 2. `conda activate ray-core-serve-tutorial`
 3. `git clone git@github.com:dmatrix/ray-core-serve-tutorial.git`
 4. `cd` to <cloned_dir>
 5. `python3 -m pip install -r requirements.txt`
 6. `python3 -m ipykernel install`
 7. `jupyter lab`
 
 If you are using **Apple M1 laptop** 🍎 follow the following instructions:
 
 1. `conda create -n ray-core-tutorial-testing python=3.8`
 2. `conda activate ray-core-tutorial-testing`
 3. `conda install grpcio`
 4. `python3 -m pip install -r requirements.txt`
 5. `python3 -m ipykernel install`
 6. `conda install jupyterlab`
 7. `jupyter lab`
 
Let's have 😜 fun with Ray @ MLOps World 2022!

Thank you 🙏,

Jules & Archit
