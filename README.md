Save this here.

GitLab Runner is an application that works with GitLab CI/CD to run jobs in a pipeline. An open source continous integration service included with GitLab. Used to run jobs & send results back to GitLab.

				STEPS TO RUN GitLab CI
STEP 1: Install GitLab runner
		Install gitlab runner to your system
		> https://docs.gitlab.com/runner/install/linux-manually.html
		syntax> gitlab-runner --version (Check gitlab version on CLI)
			>	gitlab-runner.exe install (To install gitlab-runner)

STEP 2: Register GitLab Runners
		> gitlab-runner register
		To get gitlab-runner token, follow steps below;
			> Project > Settings > CI/CD > Runners > Expand > copy Token under "Set up a specific Runner manually"
			Tags are important in GitLab Runners (Pipeline in general)
STEP 3: Start gitlab runner
		sudo gitlab-runner start
		sudo gitlab-runner.exe start
		
STEP 4: Check if runner is activated on your GitLab Account.







GitLab CI/CD

STEP 1: Add .gitlab-ci.yml in the root folder of your project/repo

STEP 2: Commit and push file to gitlab repo

STEP 3: Create GitLab runner for the project 
	> Project > Settings > CI/CD > Runners > Expand > Create a runner
	
STEP 4: Start the runner

STEP 5: Make any change in the project > commit > push



sudo docker run -d -t --name "xmccontainer" xmc-image:dev
sudo docker exec -i -t 8f4979bc5521 /bin/bash
sudo docker build -t xmcimage.azurecr.us/xmcimage/xmc-image:dev
sudo docker push xmcimage.azurecr.us/xmcimage/xmc-image:dev

sudo docker build -t devops/xmc-image:dev




https://www.youtube.com/watch?v=2HHYfy1pJAw

Docker to Azure: https://www.youtube.com/watch?v=New8K6R0hz8

Azure setup: https://docs.microsoft.com/en-us/azure/developer/ansible/install-on-linux-vm?tabs=azure-cli
https://www.youtube.com/watch?v=JZwHIytkyvI


Build Azure Instances using Ansible: https://gist.github.com/dmccuk/9705c86f688d78594281bdf16fee8388




* Build versioning (Tag versioning with ansible)

* Create ansible Test/demo/practice build environment to developers

* Unit Testing
