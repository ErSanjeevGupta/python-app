Build a deployment pipeline to deploy a Hello world app in Python using GitHub Actions. Attach the GitHub git repo (public) 

In this workflow:

It's triggered on pushes to the main branch.
It uses the latest version of Ubuntu as the runner.
It checks out the code from the repository.
It sets up Python 3.10.13
It installs any dependencies listed in a requirements.txt file (create this file if needed).
Finally, it runs the deploy.py script to deploy your "Hello World" app.
