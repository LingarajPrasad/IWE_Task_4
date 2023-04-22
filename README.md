TASK 4:

Create a GitHub Repository with { package.json and server.js }.

Write a Dockerfile for the following and add that to the repo.

Connect the repo with the Jenkins webhook.

Jenkins should be connected to a worker node which has docker and git installed in it(worker).

Configure a Free Style job to get triggered from both remote script and webhook as well.

The job should build an image from the repository and the push the same image to the docker hub.

The job should run on the worker machine not on master.

v0.0.1
v0.0.2
