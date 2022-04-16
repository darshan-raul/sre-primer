# sre-primer
dev - ops 
faster realease process
but not stable
>> no dedicated role to maintain stability

## HIGH LEVEL definition

Software engineers doing operations work

sre is what happens when you treat operations as a software problem and staff
it with a bunch of software engineers

SRE:
- teams are made up of software engineers
- build and implement software to improve the reliability og their systems


## what causes unreliaility
- changes in infra
- changes in platform
- changes in services and application

- But changes cant be avoided

- SRE tries to automate the process of evaluation the effects the changes will have

## Terms

- SLA 
	- for accessibility
	- for response time
	- for error rate
	- Business people and engineers collaborate to decide this

- Error budget: 
	- Allowed downtime of a service
	- Teams can "SPEND" error budget on making unreliable changes


## SRE Tasks

1. Automation : create automated processes for operational aspects
2. Proper monitoring: observability of system performance
3. Observailibty for detecting issues
	- ensure correct person is notified
	- all the needed information included
4. do on-call support
5. post-mortem - analysis post-issue/post-outage


## shift left

- When you have an architecture which has following in place:
	- high availability
	- reliability
	- self healing

- Then one small bug will not cause outage
- so many issues will happen for things to go wrong

## References:

https://www.youtube.com/watch?v=OnK4IKgLl24 - What is SRE | Tasks and Responsibilities of an SRE | SRE vs DevOps


## Agile

https://www.youtube.com/watch?v=km7n3DI5IWk
https://www.youtube.com/watch?v=KNBHQ0pyaG8
