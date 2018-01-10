# Datascience collateral work

This repository contains documents pertaining to various data science methods.

## Run the server

On Linux, take the following steps to launch a Juypter notebook server

* Install [docker](https://docs.docker.com/engine/installation)
* Clone this repo
* Execute ```./scripts/run_docker``` from the root of the cloned repo

On a first execution, docker will download if necessary
the [jupyter/datascience-notebook](https://github.com/jupyter/docker-stacks) container which may take a while.
The notebook server will launch, and as part of the startup message will provide a link including an access token. Opening
this link on a browser will then give access to all of the notebooks.
