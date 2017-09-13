# 2017-09 Raleigh Puppet User Group Meeting notes
## RPUG News
+ No meeting in October due to PuppetConf in October
+ Most likely next meeting Monday, Nov 6, 2017 6:30 PM in Cary

## Local Triangle News
+ [All Things Open October 23 - 24, 2017 at Raleigh Convention Center in Raleigh](https://allthingsopen.org/)
  - *More than 200 sessions will be featured, the most ever*
  - *A world-class and diverse 200 speakers will be featured*
  - *More extended/workshop sessions than ever before*
+ [ATO Schedule now available](http://allthingsopen.org/schedule/)

## Puppet ecosystem community announcements
+ [There is still time to get 10% off your PuppetConf 2017 ticket so register by September 25](http://bit.ly/2wXaNRH)
+ [Gary Larizza‏ - "My time at Puppet has come to an end, but my consulting has not! TL;DR: joining @0xEFF at http://openinfrastructure.co!"](http://garylarizza.com/blog/2017/08/25/some-other-beginnings-end/)

## Puppet ecosystem software announcements and news bits
+ [Foreman 1.16 Schedule of release](http://projects.theforeman.org/projects/foreman/wiki/Foreman_116_Schedule)
  - According to foreman-dev mailing list, there have been a number of reasons for the delays, but I imagine that they will be able to have it release in the next 5 to 6 weeks
+ [Puppet Enterprise 2016.4.7 and 2017.2.3 available](https://groups.google.com/d/msg/puppet-announce/gRK35ZoF1GE/K5vImdnlBgAJ)
  - *These releases include fixes to address security vulnerabilities in Java and nginx, as well as a number of other bugfixes and improvements.*
+ [Puppet agent 1.10.7 released](https://groups.google.com/d/msg/puppet-announce/2mYRt2X9Piw/_wkOQJuOAgAJ)
  - Puppet (4.10.7), Facter (3.6.7), and pxp-agent (1.5.5)
+ [Puppet Server 2.8.0 available](https://groups.google.com/d/msg/puppet-announce/L1SKTFu5wVo/52KNh607AQAJ)
  - *The headline feature is that the puppetserver now automatically reloads the CRL (certificate revocation list) when a node's certificate is revoked,*
+ [Puppet agent 5.1.0 released](https://groups.google.com/forum/?utm_medium=email&utm_source=footer#!msg/puppet-users/1JX7GrS2SwM/h88sfeJuBAAJ)
  - *Components updated in this release include Puppet, Facter, and MCollective.*
+ [Puppet Development Kit (pdk) 1.0.x available](https://groups.google.com/d/msg/puppet-dev/qcPAOuqOeXs/DTqzHp6nBwAJ) - *With the PDK you can*
    + *Quickly get started with module development best practices and tools to develop, test and publish high-quality Puppet modules with confidence*
    + *Shift quality to the left by catching issues earlier and faster, before Puppet code is applied to live infrastructure*
    + *Unit test modules from their workstation to ensure that Puppet code is creating and managing resources as intended*
+ [Looking at public Puppet servers](https://infosec.rm-it.de/2017/07/18/looking-at-public-puppet-servers/) - "*Out of those 2500 servers: 89 immediately signed our certificate. Out of those 89: 50 compiled a valid catalog that could have been applied directly. 39 tried to compile a catalog and failed with issues that could potentially be worked around on the client but no time was spent on that.*"
+ [Kubernetes Manifest Templating with ERB and Hiera](https://roobert.github.io/2017/08/16/Kubernetes-Manifest-Templating-with-ERB-and-Hiera/)
  - *So why erb-hiera? Because it is simple, and our teams are used to the combination of ERB templating language and Hiera due to their familiarity with Puppet. We can use the same tool across multiple code bases which manage our infrastructure and applications.*
+ [The Wikimedia Foundation’s Discovery Analysis team recently switched to a Puppet-based configuration for their metrics dashboards.](https://blog.wikimedia.org/2017/08/21/discovery-dashboards-puppet/)
  - *In this post, we share resources and tips for learning Puppet for non-Technical Operations (Ops) people, and - as an educational exercise for newcomers - explain how the new configuration works.*
+ [Harden Debian 9 Using Puppet](http://bit.ly/HardDeb)
+ Puppet tips from Example42 blog:
  - [Tip of the Week 32 - Puppet class indirection via Hiera](https://www.example42.com/2017/08/07/class-indirection/)
  - [Tip of the Week 33 - Testing a control-repo with Vagrant](https://www.example42.com/2017/08/14/testing-a-control-repo-with-vagrant/)
  - [Tip of the Week 34 - Encrypt your secrets with Hiera eyaml](https://www.example42.com/2017/08/21/encrypt-your-secrets-with-hiera-eyaml/)
  - [Tip of the Week 35 - GIT workflow for Puppet control-repositories](https://www.example42.com/2017/08/28/git-workflow-on-control-repo/)
  - [Tip of the Week 36 - Testing any role on any OS with a PSICK control repo](https://www.example42.com/2017/09/04/testing-any-role-on-any-os-with-a-psick-control-repo/)
  - [Tip of the Week 37 - Automated, reusable hiera eyaml setup](https://www.example42.com/2017/09/11/automate-reusable-eyaml-setup/)

## Selected news items from Puppet.com Blog:
+ [2017 DevOps Salary Report](https://puppet.com/resources/whitepaper/2017-devops-salary-report) has info on:
  - *Which job titles yield the highest salaries — and which are becoming more or less common.*
  - *How IT manager salaries have changed around the world since last year.*
  - *How the amount of manual configuration management people do affects their salaries.*
+ ['Puppet Podcast: Introducing the Puppet Development Kit'](https://puppet.com/products/capabilities/puppet-podcast-introducing-puppet-development-kit-pdk)


# Meeting's topic: DevOpsDay Raleigh / PuppetConf
+ [DevOpsDay Raleigh 2017 Schedule](https://dodral2017.busyconf.com/schedule)
+ [Twitter search for #devopsdaysrdu?f=tweets&vertical=default&src=hash ](https://twitter.com/hashtag/devopsdaysrdu?f=tweets&vertical=default&src=hash)
+ [Ken Mugrage - 'DevOpsDays Raleigh Follow Ups'](https://kenmugrage.com/2017/09/07/devopsdays-raleigh-follow-ups/)
+ From DevOpsDay Raleigh organizers - "*Also, as promised, we are collecting all presentations. [You may access them via the dropbox link](https://www.dropbox.com/sh/a2giltamv85wh3s/AAD7_os1xp2s7WQnmHcbt-IRa?dl=0). We will also add the recorded videos to this folder in the next two to three weeks*"
+ [PuppetConf 2017 Schedule](https://puppetconf17.sched.com/)
