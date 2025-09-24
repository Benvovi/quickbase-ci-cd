# Quickbase CI/CD Pipeline

## Project Overview
This repository contains a CI/CD pipeline example using GitHub Actions to automate testing and deployment of Quickbase scripts.

## Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/Benvovi/quickbase-ci-cd.git


Install Python dependencies:

pip install -r requirements.txt


Create a GitHub secret named QB_USER_TOKEN with your Quickbase token.



CI/CD Workflow

The workflow runs on push or pull request to the main branch.

Steps:

Checkout the repo

Setup Python

Install dependencies

Run unit tests with pytest

Deploy Quickbase script (quickbase_pipeline.py) using QB_USER_TOKEN



Notes for the Reviewer

Since this is currently set up with a personal Quickbase token, an actual app may be needed to fully test deployment.

The workflow can be cloned and run by another user after setting up their token.



---

### **Step 3: Commit and push README**
```bash
git add README.md
git commit -m "Add deployment notes and project documentation"
git push

