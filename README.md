# Requirment

* Git:
    One master branch:
        Whenever you push new code, its pipeline should start right away.

* Terraform:
    Centralized configure:
        Everything will go into a single ‘main.tf’ file.

* GitLab CI:
    Basic stages:
        - Checkout source
        - Build image from source code
        - Push to an image registry (e.g., Docker Hub)
        - Release (pull the latest image and then perform a deployment) and this stage should not be active when you push your code to a feature    branch (if you don’t choose the first tick in  the Git section)

* Ansible:
    All-in-one file configure

* Docker
    Simple web image

* Grafana
    Use default Dashboard provided
