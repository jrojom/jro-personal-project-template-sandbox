# 000-personal-project-template

This projects acts as a template for personal projects. It will include a pre-defined ci/cd pipeline that will deploy all type of Control-M artifacts.


# Standard pipeline and folders

This templates includes standard folder for each artifact type. The .gitlab-ci.yml will pickup any artifact in this repository and deploy it to the different SaaS tenants. 

# Branches

The .gitlab-ci.yml works based on 2 branches:
- __pre-prod__: The content of this branche will get deployed to the pre-prod tenant
- __master__: The content of this branche will get deployed to all three production tenants (APJ, Americas and EMEA>)

# Group variables

We are using variables on the top level group in 
