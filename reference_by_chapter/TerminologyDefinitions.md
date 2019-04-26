---
title: Terminology Definitions: Useful References
---

# Terminology Definitions: Useful References

## CI related Articles

[CI on a Dollar a Day by James Shore](http://www.jamesshore.com/Blog/Continuous-Integration-on-a-Dollar-a-Day.html)

[Continuous Integration by Martin Fowler](http://www.martinfowler.com/articles/continuousIntegration.html)

## Relevant Books

[Infrastructure as Code: Managing Servers in the Cloud by Kief Morris](https://www.amazon.com/dp/B01GUG9ZNU/)
+ This is a fantastic book for gaining an overall exposure to the various pieces of a continuous delivery build pipeline. Any team considering building out a new continous delivery build pipeline should read this book cover to cover before making any long-term tooling decisions.

[Continous Delivery: Reliable Software Releases through Build, Test, and Deployment Automation by Jez Humble and David Farley)(https://www.amazon.com/dp/B003YMNVC0)
+ Although the tool choices are very dated, the overall intentions are better explained than they are in Infrastructure as Code. In contrast, when looking at tool choices forget Continuous Delivery and read Infrastructure as Code.

## Various Infrastructure as Code Tools

The tooling landscape around continuous delivery has evolved quite a bit and continues to evolve rapidly. I recommend you do a good bit of research to figure out which tools are currently optimial for your needs before committing to a given choice. Although any decent choice can probably be made to work, there will inevitably be enough lock-in to make switching frameworks painful.

[Puppet](https://puppet.com/)

[Chef](https://www.chef.io/chef/)

[Ansible](https://www.ansible.com/)

[SaltStack](https://saltstack.com/)

[Terraform](https://www.terraform.io/intro/vs/index.html)
+ Terraform understands the overall deployment topology and provides cross-node orchestration, leaving the node specific details to Chef, Puppet, Ansible and the like.

[Kubernetes](https://kubernetes.io/)
+ Although not strictly an Infrastructure As Code tool, some of what is done with Terraform can alternatively be done using a Docker orchestration framework such as Kubernetes or Docker Swarm.
+ I have not done the hands-on work to build out a complex CD pipeline in a few a years. Since that time things have evolved quite a bit. I believe some of the orchestration work which used to require writting a lot of bespoke code is now more readily available off the shelf. 

[Why we use Terraform and not Chef, Puppet, Ansible, SaltStack, or CloudFormation by Yevgeniy Brikman of Gruntwork](https://blog.gruntwork.io/why-we-use-terraform-and-not-chef-puppet-ansible-saltstack-or-cloudformation-7989dad2865c)
