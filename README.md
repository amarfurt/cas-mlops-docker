# cas-mlops-docker
Docker exercise for MLOps lecture in CAS Machine Learning at HSLU.

## Docker
If you don't have Docker installed on your system, you can also use [Play with Docker](https://labs.play-with-docker.com/).

## Tasks
1. Look at the arguments of the `main.py` script. You can change the training arguments, and you will have to provide the Weights & Biases API key.
2. Write a `Dockerfile`. For orientation, take a look at the Dockerfile from the [Getting started guide](https://docs.docker.com/get-started/02_our_app/#build-the-apps-image). Think about how you can pass arguments to your main script.
3. Build a Docker image with `docker build -t <image-name> .`
4. Run your Docker image with `docker run -it <image-name>` and any arguments you may have. Check your Weights & Biases account to see if training is properly logged.
