# CoreOS baremetal provisioning with Terraform, Ignition and Matchbox

**Sent on**: 2017/10/11

**Status**:  accepted

**Author**:  Rafael Porres Molina

**Slides**:  TBA

**Proposal**: http://cfgmgmtcamp.eu/schedule/terraform/CoreOS.html

**Abstract**:

Building your infrastructure in baremetal servers is a very interesting and cost-effective option, especially in these container period where we can leverage the power of orchestrators like kubernetes. Baremetal is of course less flexible and it comes with tasks long forgotten in our cloud-based days: booting management and configuration. CoreOS is a good and popular choice as a base OS for a container-based system. It is also interesting due to the tools it has to make booting and OS configuration a much simpler task. In this talk Im going to describe two of them: Matchbox and Ignition and how we can integrate them in our Terraform infrastructure description using specific providers for it. This is part of a general approach towards immutable infrastructure provisioning.
