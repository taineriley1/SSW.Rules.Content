---
type: rule
archivedreason: 
title: Do you stress tests your infrastructure before testing your application?
guid: df761ab7-4a69-48a9-a4b7-d04d6b07636a
uri: do-you-stress-tests-your-infrastructure-before-testing-your-application
created: 2016-04-28T18:22:45.0000000Z
authors:
- id: 3
  title: Eric Phan
related: []

---

The infrastructure that your application is deployed to is often never tested but can be the culprit for performance issues due to misconfiguration or virtual machine resource contention. We recommend setting up a simply load test on the infrastructure like setting up a web server that serves 1 image and having the load tests simply fetch that image.

This simple test will highlight:

<!--endintro-->

* Maximum performance you can expect (are your goals realistic for the infrastructure)
* Identify any network related issues
* Uplink bandwidth, DDOS protection, firewall issues

<dl class="image">&lt;dt&gt;<img src="infratests.jpg" alt="infratests.jpg">&lt;/dt&gt;<dd>Figure: Work out the maximum performance of the infrastructure before starting</dd></dl>
**Note:** if you have other servers in the mix, then you can make another simple test to pull records from the database to check the DB server as well.