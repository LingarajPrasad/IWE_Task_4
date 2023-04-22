1. create a git hub repo with { package.json and server.js }
2. create a "Dockerfile" who can:
	i. connect the repo with jenkins webhook
	ii. Jenkins should be connected to a worker node which has docker and git installed in it(worker).
	iii. Configure a Free Style job to get triggered from both remote script and webhook as well.
	iv. The job should build an image from the repository and the push the same image to the docker hub.
	v. The job should run on the worker machine not on master.
