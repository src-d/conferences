# Predicting the future of Kubernetes from its code

**Updates**:  https://github.com/src-d/conferences/issues/106

**Sent on**:  TBA

**Status**:   proposed

**Author**:   Francesc Campoy

**Slides**:   TBA

**Proposal**: https://events.linuxfoundation.org/events/kubecon-cloudnativecon-europe-2019/cfp/

**Abstract**:

The famous Conway's law states that "organizations which design systems ... are constrained to
produce designs which are copies of the communication structures of these organizations".
In this talk, we invert that law and study an organization by analyzing the artifacts it generates.

We will cover the metrics that we can use to extract insights from the Kubernetes codebase,
including github.com/kubernetes and the younger github.com/kubernetes-sigs and
github.com/kubernetes-incubator organizations.

The goal of the talk is to show how we can observe past decisions and events to their effects on the code.
We will observe technical decisions, like the migration to [Bazel](https://bazel.build), and
social transitions like how contributions from different organizations have been distributed
across projects over time, or how, as the project approaches 2 millions lines of code, it shows
clear
signs of maturity.

Once we've ensured we can correlate past events to their effect on the source code, we will use the
trends we can currently observe on the code base to make informed predictions on the future of the
Kubernetes community.

**Benefits to the ecosystem**

We believe adopting the tenets of Code as Data can be very beneficial for all the members of the
Cloud Native Computing Foundation, as well as all players in both open and closed source creators.

We have focused a lot on the observability, monitoring, and metrics we can extract from our runtimes,
but rarely we have helped to make informed decisions by using the insights dormant in our codebases.

The same techniques used to analyze the health of the Kubernetes community can be used to not only
analyze but also influence the health and processes of any community of developers. This is even more
the case when we consider digital transformation initiatives, such as the adoption of innersource or
the migration to cloud environments, for which managing risks is essential to success.

**Notes**:

Based on the Kubernetes analysis published during Kubecon Seattle 2018.