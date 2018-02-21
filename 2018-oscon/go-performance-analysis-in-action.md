# Go performance analysis in action

**Updates**:  https://github.com/src-d/conferences/issues/9

**Sent on**:  2018/01/30

**Status**:   accepted

**Author**:   Francesc Campoy

**Slides**:   github.com/campoy/go-tooling-workshop

**Proposal**: N/A

**Description**:

We'll walk through the tools that make Go a great programming language, from the well known “go” tool to lesser known tools that allow you to profile, debug, and understand the performance of your programs.

We’ll also learn how to tune Visual Studio Code as a Go editor, although you are welcome to use any other editor—most provide great integration with Go.

**Abstract**:

I have developed a full day workshop for Go tooling, this workshop will cover the third chapter of github.com/campoy/go-tooling-workshop.

This chapter includes the following topics:

1. Introduction to performance

What is performance, how do we even measure it? Using the time command, Apache Benchmark, and others.

2. Testing and benchmarking

Writing unit tests in Go is very simple, and converting them into benchmarks is an easy change too. Once we have benchmarks we can keep track of how performant our functions are.

3. Profiling

What is performance profiling? What are the benefits and limitations?
We'll see how to use pprof for CPU and memory profiling, and how to display those results in the famous flame graphs.

4. Runtime Tracing

This is where Go shines. One of the limitations of pprof is that in order to get more detailed results we need to increase the sampling frequency. Runtime Tracing inverses the responsibility and makes the runtime log for the events we care about.
This allows for a complementary point of view of performance that shows us what the program is doing when nothing is happening. Thanks to this we'll understand when there's too few or too many goroutines, as well as when system calls are slowing down our program.

**Takeaways**

By the end of the workshop you'll have the tools to analyze any given program and understand the possible causes of a lack of performance.

You will also know which tools works better for each kind of performance issue: tracing, pprof, and more.

**Prerequesite knowledge**:

A basic knowledge of Go.

**Hardware/Software requirements**:

A laptop with:
- git
- Go 1.9 or newer
- the repository github.com/campoy/go-tooling-workshop
- http://www.graphviz.org/download/
