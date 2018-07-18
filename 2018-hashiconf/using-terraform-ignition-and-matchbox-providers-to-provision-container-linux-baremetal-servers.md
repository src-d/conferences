# Using Terraform and the Ignition and Matchbox providers to provision Container Linux baremetal servers

**Sent on**: 2018/07/16

**Status**:  sent

**Author**:  Rafael Porres Molina

**Slides**:  TBD

**Proposal**: TBD

**Abstract**:

Building your infrastructure in baremetal servers is a very interesting and cost-effective option, especially in these container period where we can leverage the power of orchestrators like Kubernetes. Baremetal is of course less flexible and it comes with tasks long forgotten in our cloud-based days: booting management and configuration. CoreOS is a good and popular choice as a base OS for a container-based system. It is also interesting due to the tools it has to make booting and OS configuration a much simpler task. In this talk I'm going to describe two of them: Matchbox and Ignition and how we can integrate them in our Terraform infrastructure description using specific providers for it. This is part of a general approach towards immutable infrastructure provisioning.
