# Assignment Name

Description..

# Precondition:
1. Clone this project locally
2. Add your completed questionnaire and CV in `docs` directory, and push changes in your first PullRequest.  


# Requirements

1. Create two plain  web servers in python (or we can provide one for you)
2. Define Dockerfile for that web service
3. Define docker-compose or helm chart that includes the services above
4. Define Terraform or Ansible specs in order to manage entire local infrastructure from code.
5. Develop bash or python script (app.sh or app.py) that will bootstrap entire process in one command (from scratch)
That script should combine all components developed in the previous steps and spin up all required instances for testing

# Expectations:
1. A command `./app.sh start` should spin up the local infrastructure and open http://localhost URL in the browser.
2. Using `./app.sh stop` command script should tear the infrastructure down, and 
3. With the command `./app.sh destroy` all resorces should be completely destroyed from the system (cached volumes, docker images, uploaded files, etc.)


# Contribution

1. All changes should be submitted in a PullRequest (PR)
2. If you have any questions or ambiguity, feel free to create an ISSUE on this repo. 
Discussion should not take place outside of the repo. Just to mention: More questions 
usually doesn’t mean lack of knowledge but complete opposite. So, don’t assume that you understand if that’s not the case. 
