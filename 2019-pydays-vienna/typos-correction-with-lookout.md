# Title of the Talk

**Updates**:  https://github.com/src-d/conferences/issues/133

**Sent on**:  -

**Status**:   on preparation

**Author**:   Irina

**Bio**: Junior Machine Learning Engineer at source{d}. Persue Master's degree of Computer Science and Data Analysis at MIPT (Moscow
Institute of Physics and Technology). Study at Yandex School of Data Analysis.

**Slides**:   -

**Abstract**:

We all make typos in code. Some are filtered at an early stage with help of IDEs or during compilation and tests.
Still big part of them leaks into the production code: there are more than 1 million typos-connected issues on GitHub (over 100k are open).
So in the end huge amount of typos get to be ponted-out by human reviewers in PRs (or even in production).
It takes a lot of time, concentration and manual correction. And it's very annoying. The time has come to bring some automation in.

I present typos lookout analyzer - the tool for automatic correction of typos inside source code in Pool Requests on GitHub.
It's easy-to-use: when someone creates a PR to your repo, they get a list of automatically generated comments, marking down typos and
suggesting corrections for them.

The analyzer is powered by the Lookout sdk https://github.com/src-d/lookout-sdk. It is a toolkit, that provides an easy way 
for creating and running source code analyzers.

Typos analyzer is written on Python. The correction itself is done by a model, which uses Machine Learning and fast Fuzzy Search
algorithms. The model suggests corrections with regard to specific project and general code conventions. It also accounts for
the word's context.

**Notes**:

This is my first talk and conference that I visit, so I desperately need guidence.
