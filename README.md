# README

This repository was created with NataSquad AI Hackathon.

## Work Environment

### Build docker image

`docker build -t datascience:1.1 .\docker`

This image contains the latest tensorflow version with support for jupyter notebook and GPU.

Some other packages were installed:

- Scikit learn
- Auto scikit learn
- Pandas
- Seaborn

### Run container

To run the container this command can be executed in windows terminal:

- `docker run -it --rm -v ${PWD}:/tf/notebooks --gpus all -p 8888:8888 datascience:1.1`

Then open a browser with the authentication link provided in the logs.

### Run devcontainer

Open this folder in VSCode and run as a devcontainer with the information provided in `.devcontainer`.

## Problems

The main problem to submit for hackathon evaluation is the 8th problem related to computer vision. This problem contains a more detail explanation than other problems solved in the competition.
