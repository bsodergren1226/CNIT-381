# CNIT-381
Weekly Labs for CNIT 381
## Week 1
Created the repository, configured Git, cloned it locally, and made my first commit.

## Week 2
Practiced team Git collaboration with a partner: feature branches, pull requests, code review, and resolving a merge conflict on a shared network inventory site. 

Practiced team Git collaboration using VS Code and Git commands: feature branches, commits, pushes, pull requests, code review, squash merging, and resolving a merge conflict while building the UW-Stout CNIT Cybersecurity Technology Hub.
## Week 3
Containerized a duplicate-IP checker with Docker and published the image to Docker Hub.

## Week 4
Built a network config pipeline: an intent file plus a generator, containerized, with CI/CD that regenerates and validates the configs on every change. 

## Week 5
Called the Github REST API from Python to read my repo and create an issue.

## Week 6
A Python checker for our IP address plan, packaged in
Docker, run by GitHub Actions on every push, that opens a GitHub issue
through the API when the plan has errors.

https://github.com/bsodergren1226/ip-plan-check

## Week 7: CML installation
Got CML up and running and accessed the CML dashboard using the VMs IP

## Week 8: OSPF by Hand, Then Automated
What I did: configured OSPF manually, ran a provided playbook that automated it,
and wrote my own playbook to back up the configs. 

## Week 9
This week, I created a new network topology in Cisco Modeling Labs with two routers, a Layer 2 switch, an Ubuntu server, and an external connection. I manually configured IP addresses and SSH access on the network devices so Ansible could communicate with them.

I then created an Ansible inventory and four playbooks to configure loopback interfaces, enable EIGRP routing, set login banners, and back up device configurations. I verified the routing connections and tested the playbooks a second time to confirm that the configurations did not need to be changed again.

This lab helped me understand how manual network configuration and automation work together. I also learned how Ansible uses inventory groups, variables, and playbooks to manage multiple devices more efficiently.

Week 9 GitHub Repository: https://github.com/bsodergren1226/cnit381-week9
