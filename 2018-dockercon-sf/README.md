# Deploying distributed apps to your CLI with Kubernetes

**Updates**:  https://github.com/src-d/conferences/issues/11

**Sent on**:  2018/01/18

**Status**:   proposed

**Author**:   Francesc Campoy

**Slides**:   TBD

**Proposal**: N/A

**Abstract**:

Now that Docker ships with a local Kubernetes cluster it's time to consider what new possibilities this opens. At source{d} we develop many applications that require multiple pieces to work: databases, web servers, and many others.

We use helm charts, so it is very simple to get an installation running on your own cluster. But what about offline usage? This talk explains a solution to the problem and analyzes its pros and cons.