---
layout: post
title:  "Opensource at Redhat/JBoss - Singapore Java User Group"
date:   2017-02-22 15:32:27 +0800
categories: jekyll update
---

<iframe width="560" height="315" src="https://www.youtube.com/embed/J7qFOxi160k?ecver=1" frameborder="0" allowfullscreen></iframe>

Bruno Georges leads a team of 150 people at RedHat working for different Open Source projects such as JBoss, Undertown and Hibernate. During this presentation he whole about how they do Open Source at JBoss, Red Hat.

The presentation is quite general about JBoss and RedHat. Some projects introduced during this talked will get a dedicated talk at the [VoxxedDays Singapore](http://voxxeddays.com/singapore/) conference.

**History**

As an introduction Bruno presented the history of JBoss and its evolution over the years. Almost everyone knows JBoss as an application server. JBoss first release (v0.0.4) was released on Febrary 1999 and was acquired by RedHat in 2004.

Over the years, JBoss AS (Application Server) has been renamed renamed Wildfly. Throughout its history JBoss saw a few game changers with OpenShift in 2012, Backend as Service and API Management in 2014.

**Open Source model at JBoss**

Bruno then explained the Open Source model at RedHat. The open source culture is about Collaboration and Transparency (everything, and discussions happen in public, applies to JBoss projects too). Shared problems are solved faster and working together eventually leads to standardization.

Every open-source projects RedHat is woking on or with is certified and gets support from the company, That is basically their business model around open source. Some Open Source projects gets a new name when certified and sold with support. For instance, Apache Camel is rebranded as Red Hat JBoss Middleware and Fedora as Red Hat enterprise.

**Java projects at JBoss RedHat**

JBoss has been a major contributor for Java and the OpenJDK. They have worked on the Java EE specification, the ARM 64bits support for the OpenJDK, the Shenandoah project (ultra low latency garbage collector) and Thermostat (JVM instrumentation).

The number of Open Source projects in which JBoss Red Hat is involved is honestly quite impressive. Some examples are: Vert.x, Keycloak (security), Undertow, Wildfly (Java EE), Netty, Ifinispan (data grid), Awkular (APM), etc. When they say their business model is around open source, they really mean it.

**Microprofiles**

With Wildfly Swarm Bruno introduced us the microprofile specification. Microprofile is about only picking up the specs of Java EE that are required to run a application and allows having lightweight embedded runtimes (see the get started example at [http://wildfly-swarm.io](http://wildfly-swarm.io)). Bruno mentioned a talk from Antonio Congalves that is worth having a look to if you are interested in Java EE microprofiles: [https://www.youtube.com/watch?v=iBJ8FlUA3ok](https://www.youtube.com/watch?v=iBJ8FlUA3ok)

As of today the microprofile specification only includes JAX-RS, CDI, JSON-P. Wildfly Swarm is ahead of the specification and implements other Java EE APIs.

There is a group of teams working on the specification ( [https://microprofile.io/](https://microprofile.io/)). The vision of JBoss and its strategy is to make a first release, then rapidly iterate and innovate, then building a consensus in order to standardize. This process aims at preventing the specification of being &quot;frozen&quot; for years holding back progress and innovations.
