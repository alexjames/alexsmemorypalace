---
layout: page
title: SLA
categories: software
---

###### Basics
 * SLA which stands for Service Level Agreement is a formal specification of the gaurantees of availability and performance characteristics of a system.
 * It is theoretically and practically impossible for a system to be 100% available.

###### 9's of availability

| | Availability | Downtime per year |
| --- | --- | --- |
One Nine | 90% | 36.53 days
Two Nines | 99% | 3.653 days
Three Nines | 99.9% | 8.7 hours
Four Nines | 99.99% | 52.6 minutes
Five Nines | 99.999% | 5.26 minutes

###### Typical SLAs
 * Four nines are more common.
 * Even if a system claims to have an SLA of 100% uptime, what that usually means is that the company will compensate customers if the SLA is breached at an agreed upon rate for each percentage point of availability which was not provided. However, practically all contracts only have these contractually obligated payments kick in only after a certain threshold of downtime e.g. customers are only compensated after 20 minutes of downtime a year, etc. This allows 100% uptime to be a marketing term used by vendors. This isn't a bad thing because having constraints such as this incentivizes vendors not to breach SLAs.
