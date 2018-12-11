# Analyzing the Kubernetes community via its source code

**Updates**:  #112

**Sent on**:  12/10/2018

**Status**:   proposed

**Author**:   Francesc

**Slides**:   TBD

**Proposal**:  https://conferences.oreilly.com/velocity/vl-ca/user/proposal/propose/cfp/690/74838

**Abstract**:

One-sentence description of your presentation:

> Source code is much more than something you compile to create software deliverables, it is a valuable source of information that can inform you on the health of a project, its trends, and its future.

Abstract:

> In this talk, I will assess the status of the Kubernetes project and its community by analyzing its source code.
>
> We will present the kind of technical difficulties one needs to overcome in order to successfully analyze code at this scale (well over 2 million lines of code total), including language classification, parsing, etc.
> 
> Then we will cover the kind of metrics that can give us clear insights on how the project is doing, where the innovation efforts are being directed to, as well as which pieces of software seem to be the best candidates for refactoring.
> 
> The metrics will be mostly related to the two most common initiatives we've observed in the industry: Cloud Native and Innesource efforts. Therefore, we will analyze some technical guidelines and how the source code adheres to them, but also social aspects of how different teams collaborate and whether any silos exist.
> 
> Although most of these metrics will be extracted thanks to source{d} Engine (sourced.tech/engine), which provides a SQL interface to an ensemble of git repositories,the takeaways are applicable to any other techniques including bash scripts powered by the git binary and lots of patience.

**Notes**:

> Most of the analysis has already been done and will be published as a blog post during Kubecon.
>
> This talk will be the cool details on how we got to these analyses and the feedback we got from members of the community like Joe Beda.
>
> Some of the graphs we created are available here: https://docs.google.com/presentation/d/e/2PACX-1vTAqb7XSLN42hJLSWhO3uFm1rklkJ2b_m5Lk_ExhLE37IZ0ZWNDFZQvwVNUQOdrSrqlrV3K1n7QERWf/pub?start=false&loop=false&delayms=3000&slide=id.g43d36b103c_1_248
(Please do not share this link widely as it's not permanent)

Prerequisites:

> - Basic knowledge of Python and SQL programming.
> - Basic experience using git and its concepts such as branches and commits.
