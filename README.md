Tokyo Olympics Data Engineering using Azure
This repository contains code and documentation for an Azure-based data engineering project focused on Tokyo Olympics data.

Overview
The goal is to ingest, store, process, analyze and visualize Tokyo Olympics datasets leveraging Azure services like:

Azure Blob Storage
Azure SQL Database
Azure Databricks
Azure Data Factory
Azure Analysis Services

Additional technologies like Spark, Delta Lake and SQL may be used for data processing and analytics.


Repository structure


.
├── analysis # Notebooks, scripts for analysis

├── data # Tokyo Olympics datasets

│ ├── raw # Raw, immutable data

│ └── processed # Cleaned, transformed data

├── docs # Project documentation

├── pipelines # Data pipeline definitions

├── sql # SQL create scripts

├── src # Custom source code

├── .gitignore # Files to ignore from tracking

└── README.md # This file


Getting Started

# Fork the repository
# Go to the GitHub page for the repo and click on the "Fork" button in the top right

# Clone the forked repository to your local machine
git clone https://github.com/<your-github-username>/Tokyo-Olympics-Data-Engineering.git

# Change into the cloned directory 
cd Tokyo-Olympics-Data-Engineering

# Configure remotes to point to the appropriate upstream and origin repositories
git remote add upstream https://github.com/<original-repo-owner>/Tokyo-Olympics-Data-Engineering.git
git remote set-url origin https://github.com/<your-github-username>/Tokyo-Olympics-Data-Engineering.git

# Verify remote repositories
git remote -v

# Fetch updates from the upstream repository
git fetch upstream

# Merge upstream changes into your local master branch
git checkout master
git merge upstream/master


Fork the original repository to create your own copy
Clone your forked repository
Configure the remotes to point to the upstream and your forked repositories
Fetch updates from the original upstream repository
Merge upstream changes into your local clone
