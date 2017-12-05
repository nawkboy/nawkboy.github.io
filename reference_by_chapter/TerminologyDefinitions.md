---
title: Terminology Definitions: Useful References
---

# Terminology Definitions: Useful References

# CI related Articles

[CI on a Dollar a Day by James Shore](http://www.jamesshore.com/Blog/Continuous-Integration-on-a-Dollar-a-Day.html)

[Continuous Integration by Martin Fowler](http://www.martinfowler.com/articles/continuousIntegration.html)


## Various Infrastructure as Code Tools

[Puppet](https://puppet.com/)

[Chef](https://www.chef.io/chef/)

[Ansible](https://www.ansible.com/)

[SaltStack](https://saltstack.com/)

[Terraform](https://www.terraform.io/intro/vs/index.html)
+ I believe Terraform understands the overall deployment topology and provides cross-node orchestration, leaving the node specific details to Puppet, Ansible and the like.

[Kubernetes](https://kubernetes.io/)
+ Although not strictly an infrastructure as code tool, some of what is done with Terraform can alternatively be done using a Docker orchestration framework such as Kubernetes or Docker Swarm.
+ I have not done the hands-on work to build out a complex CD pipeline in a few a years. Since that time things have evolved quite a bit. I believe some of the orchestration work which used to require writting a lot of bespoke code is now more readily available off the shelf.  
