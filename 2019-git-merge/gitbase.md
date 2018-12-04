2019/02 - GitMerge - gitbase, SQL interface to Git repositories

**Updates:** https://github.com/src-d/conferences/issues/108

**Sent on:** 2018/10/18

**Status:** accepted

**Author:** Javi Fontán

**Abstract:**

At source{d} we analyze a huge amount of git repositories and extract insights on source code. To do this have created source{d} Engine, a powerful engine for language-agnostic analysis of your source code and git history. The git history part of the analysis is handled by Gitbase, an SQL database engine that is able to understand git repositories and is MySQL protocol compatible. We had to tackle some problems like solving the differences between git repository model and relational databases, create a database engine in go language, parallelize git repository access or finding ways to store and use caches and indexes. You'll learn about the journey from what began as a side project to the current state, its internals and the different solutions we approached.

**Notes:**
