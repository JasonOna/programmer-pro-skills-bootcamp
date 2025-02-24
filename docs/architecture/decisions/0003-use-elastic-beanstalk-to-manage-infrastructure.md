# 3. Use Elastic Beanstalk to manage infrastructure

Date: 2025-01-30

## Status

WIP

## Context

* ["Minimum Viable Architecture"](https://youtu.be/9Q7GANXn02k?si=8ReyfcefGrEzjbod) by Randy Shoup, advises for Platform-as-a-service.
* AWS a common platform and Elastic Beanstalk is their Platform as a Service (PAAS)

## Decision

* I will use AWS (specifically [Elastic Beanstalk](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/GettingStarted.html?pg=cloudessentials)) as our cloud provider

## Consequences

* I will build experience in back end technology
* Pipelines will be easier to manage since I am leveraging off of a PAAS type solution
* If I decide to handle infrastructure in the future, there is a possibility to replace Elastic Beanstalk
