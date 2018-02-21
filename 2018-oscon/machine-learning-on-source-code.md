# Machine Learning on Source Code: understanding large codebases

**Updates**:  https://github.com/src-d/conferences/issues/9

**Sent on**:  2018/01/30

**Status**:   proposed

**Author**:   Francesc Campoy

**Slides**:   TBA

**Proposal**: N/A

**Description**:

Machine Learning has the power of automating human activities. From spam detection to autonomous driving we benefit greatly.

But what about reviewing code? Or maybe even coding!
Not only we think this is possible but we're working on it and the whole project is open sourced.

This talk explains how we're tackling this problem, the current state, and what we predict for years to come.

**Abstract**:

This talk is an introduction to the topic of Machine Learning on Source Code: a term coined at source{d} to describe the application of techniques from Natural Language Processing, Source Code Analysis, and Big Data to large code bases.

We currently analyze millions of git repositories, including petabytes of data, and all of our code is Open Source on github.com/src-d.

The talk will cover what are the incentives of developing this kind of stack, the obstacles we've encountered, and the lessons we've learned.

The stack is currently a mix of Spark for distributed computing on large code bases and Tensorflow for training models that we can then use to predict or detect interesting features.

In addition to this, we've discovered that no matter how complex the model, it is very hard to predict accurately when the code is understood as a sequence of bytes. That's why we've developed babelfish (bblf.sh) which parses code in many languages to Universal Abstract Syntax Trees (uAST) on which we can train our models.

The whole stack is available for anyone to use and I will demo our latest applications, such as code similitude for clustering and repeated code detection, and more advanced ideas we're currently working on.

**Takeaways**

Training complex models by feeding them structured data in the form of Universal Abstract Syntax Trees is already possible. The results are very promising already and we predict much more advanced developer tooling in just a couple of years.

**Prerequesite knowledge**:

A basic knowledge of git and software development in any language.
