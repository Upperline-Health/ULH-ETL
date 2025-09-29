# ULH-ETL
# ULH-ETL Data Factory Project

## Description
This repository contains all the source JSON files for the `df-ulhetl-dev-001` Azure Data Factory instance. This ADF is responsible for ingesting, transforming, and loading data from [Source System Name] to [Target System Name].

## Key Contacts & Owners
* Jan-Michael Luis

## Deployment Process
1.  All development work is done on feature branches.
2.  Pull Requests are created to merge feature branches into `main`.
3.  Once merged, changes are published from the ADF UI, which updates the `adf_publish` branch.
4.  Azure DevOps release pipelines deploy the ARM templates from the `adf_publish` branch to UAT and Production environments.
