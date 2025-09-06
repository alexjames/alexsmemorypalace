---
layout: page
title: First Principles
categories: software
---

##### Logging vs Metrics
Logs capture detailed information about an application's behavior, events, errors. They aid in troubleshooting.
Avoid over-logging (can increase cost for log storage when high volume) and have logging levels. This allows you to
only log densely when a particular flag e.g. `DEBUG=true` is set.

Metrics are used to understand the health and performance of a system. They are used to aggregate data such as latency,
error rates and throughput.
