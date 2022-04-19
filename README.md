# GitHub REST API Client

This python script list all open PRs younger than a given days of a GitHub repo and their corresponding HEAD commit statuses. Currently, below input params have been used to run the script:<br/>
Repo: **argo-cd**<br/>
Repo owner: **argoproj**<br/>
PRs younger than: **3 days**

**NOTE**<br/>
*secrects.py* should contain the GitHub Personal Access Token in order to connect to GitHub API

**Build Container for this script:**<br/>
Replace the 'latest' tags as per the requirement
```
sudo docker build -t githubpyclient:latest .
```
**Running as Container:**
```
docker run githubpyclient
```