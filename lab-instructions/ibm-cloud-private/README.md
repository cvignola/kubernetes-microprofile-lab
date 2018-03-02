
## Overview

The initial goal of ICP Event Management is to provide basic manageability though existing IBM offerings for ICp and customer workloads in the October 2017 ICp release, so that customers can start to integrate ICp into their existing processes.  In this case, Event Management integration seeks to surface ICp platform, monitoring and logging events in Netcool Operations Insights (NOI), also known as Omnibus.

The effort is part of an overall strategy to support and then integrate DevOps and Service Management with ICp, as illustrated in the following diagram.

![image](images/Samples/DevOpsSvcMgmtToolintegration.png)


The main persona being addressed, is outlined below

![image](images/Samples/PersonaUseCases.png)


## System Context

![image](images/Samples/NetcoolContext.png)

* (a) Kubernetes events are surfaced in NOI
* (b) The Prometheus alertmanager can be configured to send events to NOI
* (c) APM and/or DevOps monitoring can send alerts as events to NOI
* (d) The logstash forwarder for ELK can be configured to also forward loge records to NOI

## Use Cases

An as an Operations Engineer, I have visibility into whether my ICp system is experiencing degradation or failures in my event console for example :


## System Flows

See System Context, above


## Customer Requirements

See "Requirements" and "Use Cases" above as a starting point.  Additional specific requirements will be added here as they are gathered.


## Reviewer Notes

Initial reviewer include (but are limited to) the following:

* Ajay Apte
* Mike Kaczmarski
* Gerd Breiter
* Robin Hernandez


## External Reviewers

## References

Issues that are being worked in the context of this Feature Spec are lined form the following epic: