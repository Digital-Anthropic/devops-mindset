# What is GitOps

GitOps is a paradigm or a set of practices that emphasizes using Git as a singlesource of truth for the declarative infrastructure and applications.

What can GitOps provide?

- infrastructure as code
  - track changes
  - review changes

Thesre are crucial to scaling any organization.


- automated deployments
  - allows changes to be deployed quickly and reliably

Ensures the live environments match the repo state.


- reproducibility and rollbacks
  - easily recreate specific states of infra or applications

Reverting or recreating quickly is crucial.

- enhanced collaboration

Empowering individuals to contribute.

TLDR of GitOps do you want to know the current state of the system, check Git repo.


# Automation tools

Terraform
- declarative based configuration
- very low entrypoint for starting
- massive developer support


# Automation providers

Do we need to spend money on providers? 
- no, but it will help us focus money on other problems.


What if i don't want to spend money on providers?
- build own solutions
- use open-source solutions
- pay engineers to build solutions / maintain them(employees or contractors)

Either way it's going to cost the organization.

The decision is up to the organization.

Terraform Cloud
- access control features out of the box
- maintains state
- includes infrastructure # where do my pipelines run?

Env0, SpaceLift, etc
- alternatives to Terraform Cloud and Pulumi Cloud
- support multiple types of automation tools

# How to choose

- focus on the problems we are trying to solve
- focus on tools already in place
- focus on features we need first

We don't care what is best or most popular


# CI/CD

They are not the same thing!!!

CI Validate code changes using automation and generating artifacts.

CD Deploy code changes using automation.
