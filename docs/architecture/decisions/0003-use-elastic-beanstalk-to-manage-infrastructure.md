# 3. Use Elastic Beanstalk to manage infrastructure

Date: 2025-01-30

## Status

WIP

## Context

["Minimum Viable Architecture"](https://youtu.be/9Q7GANXn02k?si=8ReyfcefGrEzjbod) by Randy Shoup, advises for Platform-as-a-service.

## Decision

Use Elastic Beanstalk to deploy application

## Consequences

* We will use AWS as our cloud provider
* We will be able to find developers proficient in AWS since it's a common platform
* Pipelines will be easier to manage since we are leveraging off of a PAAS type solution
* If we decide to handle infrastructure in the future, there is a possibility to replace Elastic Beanstalk
