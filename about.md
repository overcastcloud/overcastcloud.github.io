---
layout: default
---

# What is Overcast?

Scale is hard. Cloud is hard. Cloud at scale is very hard. You need cloud software. You need management tools. You need processes.

We have run large production environments for decades. We use this experience to build Overcast. We carefully pick software that scales and is stable. This takes the guesswork out building your cloud.

OpenStack was launched promising to meet the needs of not only private, but also public cloud, being simple to implement and massively scalable. It has now been 5 years and we feel OpenStack hasn't delivered on that promise.

Thousands of people have made OpenStack what it is. Each person making it solve their specific problem. It shows. It is very impressive. It supports countless hypervisors, storage backends, network devices. You can use the hundreds of settings to configure it to your heart's content.

However, many drivers and configuration combinations are not very well tested. Many features were added without regard for very large scale deployments. This also shows.

**We can do better.**

Overcast aims to be a tightly integrated, comprehensive software suite for deploying and running an OpenStack compatible cloud at very large scale.

It will include a deployment system, configuration management tooling, the cloud software itself, monitoring, etc.

Overcast is highly opinionated. We provide very few backends and configuration options. This lets us focus our efforts and drive forward scalability, stability and reliability.

Overcast Cloud uses the OpenStack API, but we're not religious about being pure OpenStack. For example, we do include an object storage service, but it's not Swift. Instead we use Ceph for both block and object storage. We do provide a Neutron frontend, but all the heavy lifting is done by OpenContrail.
