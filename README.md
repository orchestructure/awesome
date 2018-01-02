# Awesome Orchestructure

---
A community curated list of useful and interesting resources.

### Table of Contents

* [Configuration Management](#configuration-management)
  * [Ansible](#ansible)
  * [Chef](#chef)
  * [Puppet](#puppet)
* [Systems](#systems)
  * [Kernel](#kernel)
  * [Networking](#networking)
  * [Storage](#storage)
* [Microservices and Containers](#Microservices-and-containers)
  * [Kubernetes](#kubernetes)
  * [Networking](#networking)
* [Testing](#testing)
* [Performance, Metrics, and Monitoring](#performance,-metrics,-and-monitoring)
* [Programming Languages](#programming-languages)
  * [Golang](#golang)
* [Uncategorized](#uncategorized)


---


## Configuration Management

### Ansible

* [[Video] Ansible Best Practices: Roles and Modules (2017)](https://www.ansible.com/Ansible-Best-Practices-2017) -- [@tima](https://github.com/tima) --  Expands on the Ansible best practices and goes a bit deeper into role and module guidelines.

* [[Tool] Ansible Lint](https://github.com/willthames/ansible-lint) -- [@willthames](https://twitter.com/willthames) -- Ansible Linter.

* [[Tool] Molecule](https://github.com/metacloud/molecule) -- [@metacloud](https://github.com/metacloud) -- Test Harness for Ansible Roles.


### Chef

* [[Podcast] Food Fight: The Podcast where DevOps chefs do battle](http://foodfightshow.org/) -- [@foodfightshow](https://twitter.com/foodfightshow) -- Bi-weekly podcast tailored for the Chef community.

### Puppet

* [[Tool] octocatalog-diff](https://github.com/github/octocatalog-diff) -- [@kpaulisse](https://twitter.com/kpaulisse) -- Useful puppet tool from github that can easily provide a diff between puppet branches.

* [[Presentation] PuppetConf 2017: Beyond rspec -- Innovative Strategies for Confident CI](https://speakerdeck.com/kpaulisse/puppetconf-2017-beyond-rspec-innovative-strategies-for-confident-ci)  -- [@kpaulisse](https://twitter.com/kpaulisse) -- Presentation on github's infrastructure CI strategies with octocatalog-diff.


---


## Systems

### Kernel

* [[Blog] The Definitive Guide to Linux System Calls](https://blog.packagecloud.io/eng/2016/04/05/the-definitive-guide-to-linux-system-calls/) -- [@PackageCloud](https://twitter.com/packagecloudio) -- Comprehensive introduction to Linux syscalls.

* [[Blog] Linux tracing systems & how they fit together](https://jvns.ca/blog/2017/07/05/linux-tracing-systems/) -- [@b0rk](https://twitter.com/b0rk) -- Very good and in depth introduction to modern network load balancing and proxying techniques.

* [[Blog] A thorough introduction to eBPF](https://lwn.net/Articles/740157/) -- [@fleming_matt](https://twitter.com/fleming_matt) -- Introduction and History of eBPF.

* [[Blog] eBPF, part 1: Past, Present, and Future](https://ferrisellis.com/posts/ebpf_past_present_future/) -- [@im_ferris](https://twitter.com/im_ferris) -- In depth overview of eBPF and it's history.

* [[Blog] eBPF, part 2: Syscall and Map Types](https://ferrisellis.com/posts/ebpf_syscall_and_maps/) -- [@im_ferris](https://twitter.com/im_ferris) -- Continuation of in depth overview of eBFP, and how it is used.

* [[Blog] Dive into BPF: a list of reading material](https://qmonnet.github.io/whirl-offload/2016/09/01/dive-into-bpf/) -- [@Qeole](https://twitter.com/Qeole) --  Amazing collection of resources regarding BPF.


### Networking

* [[Blog] Introduction to modern network load balancing and proxying](https://blog.envoyproxy.io/introduction-to-modern-network-load-balancing-and-proxying-a57f6ff80236) -- [@mattklein123](https://twitter.com/mattklein123) --  Very good and in depth introduction to modern network load balancing and proxying techniques.

* [[Blog] Monitoring and Tuning the Linux Networking Stack: Sending Data](https://blog.packagecloud.io/eng/2017/02/06/monitoring-tuning-linux-networking-stack-sending-data/) -- [@PackageCloud](https://twitter.com/packagecloudio) --  Deep dive into tuning and monitoring the Linux Networking Stack -- tailored for sending data.

* [[Blog] Monitoring and Tuning the Linux Networking Stack: Receiving Data](https://blog.packagecloud.io/eng/2016/06/22/monitoring-tuning-linux-networking-stack-receiving-data/) -- [@PackageCloud](https://twitter.com/packagecloudio) -- Deep dive into tuning and monitoring the Linux Networking Stack -- tailored for receiving data.

* [[Blog] Illustrated Guide to Monitoring and Tuning the Linux Networking Stack: Receiving Data](https://blog.packagecloud.io/eng/2016/10/11/monitoring-tuning-linux-networking-stack-receiving-data-illustrated/) -- [@PackageCloud](https://twitter.com/packagecloudio) -- Illustrated version of previous guide to receiving data.

* [[Tool] Wireguard](https://www.wireguard.com/) -- [@EdgeSecurity](https://twitter.com/EdgeSecurity) -- Kernel level high performance VPN.

### Storage

* [[Blog] Nonblocking I/O](https://medium.com/@copyconstruct/nonblocking-i-o-99948ad7c957) -- [@copyconstruct](https://twitter.com/copyconstruct) -- Great article on the fundamentals of file descriptors and nonblocking I/O.

* [[Blog] The method to epoll’s madness](https://medium.com/@copyconstruct/the-method-to-epolls-madness-d9d2d6378642) -- [@copyconstruct](https://twitter.com/copyconstruct) -- Followup to previous article, this time covering epoll.


---

## Microservices and Containers

* [[Blog] How-to Debug a Running Docker Container from a Separate Container](https://medium.com/@rothgar/how-to-debug-a-running-docker-container-from-a-separate-container-983f11740dc6) -- [@rothgar](https://twitter.com/rothgar) -- Great troubleshooting pattern that can be applied to near any container environment.

* [[Blog] Container isolation gone wrong](https://sysdig.com/blog/container-isolation-gone-wrong/) -- [@gianlucaborello](https://github.com/gianlucaborello) -- A retrospective post on container isolation and troubleshooting odd behavior.


### Kubernetes

* [[Blog] What happens when ... Kubernetes edition!](https://github.com/jamiehannaford/what-happens-when-k8s) -- [@jamiehannaford](https://twitter.com/jamiehannaford) -- In depth overview of how a pod is scheduled within Kubernetes.

* [[Blog] An illustrated guide to Kubernetes Networking [Part 1]](https://medium.com/@ApsOps/an-illustrated-guide-to-kubernetes-networking-part-1-d1ede3322727) -- [@ApsOps](https://twitter.com/ApsOps) -- Introduction to Kubernetes networking -- without overlay network

* [[Blog] An illustrated guide to Kubernetes Networking [Part 2]](https://medium.com/@ApsOps/an-illustrated-guide-to-kubernetes-networking-part-2-13fdc6c4e24c) -- [@ApsOps](https://twitter.com/ApsOps) -- Introduction to Kubernetes networking -- with an overlay network (vxlan)

* [[Blog] How Heptio Engineers Ace the Certified Kubernetes Administrator Exam](https://blog.heptio.com/how-heptio-engineers-ace-the-certified-kubernetes-administrator-exam-93d20af32557) -- [@rosskukulinski](https://twitter.com/rosskukulinski) --  Collection of resources and links useful for studying and passing the CKA exam.

* [[Blog] Kubernetes: from load balancer to pod](https://medium.com/google-cloud/kubernetes-from-load-balancer-to-pod-3f2399637b0c) -- [@aconchillo](https://twitter.com/aconchillo) -- Collection of resources and links useful for studying and passing the CKA exam.

* [[Presentation] Kubernetes Walk Through from Technical View](https://speakerdeck.com/resouer/kubernetes-walk-through-from-technical-view) -- [@resouer](https://twitter.com/resouer) -- Technical core Kubernetes architecture overview.

* [[Presentation] Kubernetes Node Under the Hood](https://speakerdeck.com/resouer/kubernetes-node-under-the-hood) -- [@resouer](https://twitter.com/resouer) -- Deep dive into kubelet and a Kubernetes node.

* [[Podcast] TGIK8s](https://www.youtube.com/playlist?list=PLvmPtYZtoXOENHJiAQc6HmV2jmuexKfrJ) -- [@jbeda](https://twitter.com/jbeda) -- Weekly Podcast by Kubernetes co-creator Joe Beda on the Kubernetes eco-system.

* [[Tool] keepalived-cloud-provider](https://github.com/munnerz/keepalived-cloud-provider) -- [@jamesmunnelly](https://twitter.com/jamesmunnelly) -- Useful for bare metal and on-prem Kubernetes deployments.

* [[Tool] MetalLB](https://github.com/google/metallb) -- BGP based Cloud Provider - Useful for -- bare metal and on-prem Kubernetes deployments.

* [[Tool] kube-router](https://github.com/cloudnativelabs/kube-router) -- BGP Kubernetes network provider that uses IPVS/LVS and BGP ECMP -- Useful for bare metal and on-prem Kubernetes deployments.

### Networking

* [[Blog] Microservices Patterns With Envoy Sidecar Proxy: The series](http://blog.christianposta.com/microservices/00-microservices-patterns-with-envoy-proxy-series/) -- [@christianposta](https://twitter.com/christianposta) -- Deep dive into envoy and istio, parent to a series that is continuing as of 12/31/2017.

* [[Tool] Cilium](https://github.com/cilium/cilium) -- [@ciliumproject](https://twitter.com/ciliumproject) -- An eBPF based container network provider. Very high performance.

* [[Tool] Contour](https://github.com/heptio/contour) -- [@heptio](https://twitter.com/heptio) -- Kubernetes ingress controller based off Lyft's envoy.

* [[Tool] Traefik](https://github.com/containous/traefik) -- [@traefikproxy](https://twitter.com/traefikproxy) -- Golang-based load balancer / reverse proxy engine built for microservice environments.


---

## Testing

* [[Blog] Testing Microservices, the sane way](https://medium.com/@copyconstruct/testing-microservices-the-sane-way-9bb31d158c16) -- [@copyconstruct](https://twitter.com/copyconstruct) -- Very thorough article on methods and approaches to testing microservice applications

* [[Tool] Test Kitchen](https://kitchen.ci/) -- [@kitchenci](https://twitter.com/kitchenci) -- Generic Infrastructure test-harness framework

* [Serverspec](http://serverspec.org/) -- [@mizzy](https://github.com/mizzy) -- Infrastructure test suite based off the Ruby test library rspec. It requires no agent and can be used with any Configuration Management tool.

* [Inspec](https://www.inspec.io/) -- [@Chef](https://twitter.com/chef) -- Similar to serverspec, but more easily extendable and built in support for compliance style checks


---


## Performance, Metrics, and Monitoring

* [Performance Analysis Methodology](http://www.brendangregg.com/methodology.html) -- [@brendangregg](https://twitter.com/brendangregg) -- Overview of USE (Utilization Saturation and Errors), TSA (Thread State Analysis), and Off-CPU monitoring.

* [Linux Enhanced BPF (eBPF) Tracing Tools](http://www.brendangregg.com/ebpf.html) -- [@brendangregg](https://twitter.com/brendangregg) -- Very good collection of info, tools, other articles and presentations around eBPF.

* [Prometheus](https://kartar.net/2017/10/prometheus/) -- [@kartar](https://twitter.com/kartar) -- Introduction to Prometheus from one of the creators of Riemann.

* [Falco](https://github.com/draios/falco) -- [@sysdig](https://twitter.com/sysdig) -- Great tool from sysdig for auditing and reporting in a container environment.

* [Telegraf](https://github.com/influxdata/telegraf) -- [@InfluxDB](https://twitter.com/InfluxDB) -- Telegraf is an agent written in Go for collecting, processing, aggregating, and writing metrics.


---


## Progamming Languages

### Golang

* [go-patterns](https://github.com/tmrts/go-patterns) -- [@_tmrts](https://twitter.com/_tmrts) -- Curated list of golang design patterns.

* [Golang Basics: Writing Unit Tests](https://blog.alexellis.io/golang-writing-unit-tests/) -- [@alexellis](https://twitter.com/alexellis) -- Fantastic reference and starting point for writing golang unit tests.


---

## Uncategorized

* [CNCF Youtube Channel](https://www.youtube.com/channel/UCvqbFHwN-nwalWPjPUKpvTA) -- [@cloudnativefdn](https://twitter.com/cloudnativefdn) -- CNCF youtube channel, massive collection of good resources.

* [Certificatechain.io](https://certificatechain.io/) -- [@spatie_be](https://twitter.com/spatie_be) -- Handy tool to generate the full cert chain for SSL certificates.
