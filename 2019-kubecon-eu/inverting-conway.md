# Predicting the future of Kubernetes from its code

**Updates**:  https://github.com/src-d/conferences/issues/106

**Sent on**:  TBA

**Status**:   on preparation

**Author**:   Francesc Campoy

**Slides**:   TBA

**Proposal**: https://events.linuxfoundation.org/events/kubecon-cloudnativecon-europe-2019/cfp/

**Abstract**:

The famous Conway's law states that "organizations which design systems ... are constrained to produce designs which are copies of the communication structures of these organizations".
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

**Notes**:

Based on the Kubernetes analysis published during Kubecon Seattle 2018.