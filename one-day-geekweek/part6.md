# Cloud Foundry

---

A Cloud Native Platform for people who want to get stuff done.

---


# CF 101

>what problems does it solve?

* managing operating systems sucks.
* managing runtimes sucks
* managing deployment of dependencies sucks
* managing application isolation sucks
* managing deployment tasks sucks

---

## Process for deploying/scaling app on EC2 / EHC / etc

* Deploy VM (the easy part - handled by IaaS...CMDB?)
* Secure VM (or write some puppet)
* Install runtime (with what?  rpm?  tarball?)
* install dependencies (or write some scripts)
* Install application (tarball? RPM? git?)
* Start application (how?  job engine?  keep it running?)
* Modify load balancer (how?)
* Modify firewall (how?)
* Add health checks (to where?  http? tcp? )

---

# Components:
 * Router
 * UAA
 * Cloud Controller / Health Manager
 * Elastic Runtime / Diego
 * Blob Store
 * Services
 * Doppler / Loggregator

---

![](https://github.com/cloudfoundry/docs-cloudfoundry-concepts/blob/master/images/diego/diego-overview.png?raw=true)

---

#Roll that beautiful bean footage!

NHC Demo customer push, bind, scale and application view events and logs.

---



---

# Things that just happened:

* Deploy application
* Verify runtime and application is up.
* Install data services and verify active.
* Scaled an application.
* All done via Pivotal Labs or Application Manager. Can be done via CLI too.
