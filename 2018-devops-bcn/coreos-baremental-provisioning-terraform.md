# CoreOS baremetal provisioning with Terraform, Ignition and Matchbox

**Updates**: https://github.com/src-d/conferences/issues/6

**Sent on**: 2018/01/31

**Status**:  accepted

**Author**:  Rafael Porres Molina

**Slides**:  http://bit.ly/2nCCgoa

**Proposal**: -

**Abstract**:

Building your infrastructure in baremetal servers is a very interesting and cost-effective option, especially in these container period where we can leverage the power of orchestrators like kubernetes. Baremetal is of course less flexible and it comes with tasks long forgotten in our cloud-based days: booting management and configuration. CoreOS is a good and popular choice as a base OS for a container-based system. It is also interesting due to the tools it has to make booting and OS configuration a much simpler task. In this talk Im going to describe two of them: Matchbox and Ignition and how we can integrate them in our Terraform infrastructure description using specific providers for it. This is part of a general approach towards immutable infrastructure provisioning.
