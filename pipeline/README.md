Homework1

Question 1. Understanding Docker images

Run docker with the python:3.13 image. Use an entrypoint bash to interact with the container.

What's the version of pip in the image?
Answer:
@Lin-Yuan-Louis ➜ /workspaces/docker-workshop (main) $ docker run -it     --rm     --entrypoint=bash     python:3.13
Unable to find image 'python:3.13' locally
3.13: Pulling from library/python
Digest: sha256:c8b03b4e98b39cfb180a5ea13ae5ee39039a8f75ccf52fe6d5c216eed6e1be1d
Status: Downloaded newer image for python:3.13
root@98cd20b9a5c0:/# pip -V
pip 25.3 from /usr/local/lib/python3.13/site-packages/pip (python 3.13)
Answer: 25.3

Question 2. Understanding Docker networking and docker-compose

Given the following docker-compose.yaml, what is the hostname and port that pgadmin should use to connect to the postgres database?

Answer: localhost:5432

Question:7

teraform init, terraform plan -auto-apply, terraform rm