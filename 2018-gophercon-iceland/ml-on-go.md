# Machine Learning On Go Code

**Updates**:  https://github.com/src-d/conferences/issues/7
**Sent on**:  2018/03/03
**Status**:   proposed
**Author**:   Francesc Campoy
**Slides**:   TBA
**Proposal**: https://www.papercall.io/talks/64650/children/64651

**Abstract**:

We've all wondered how to use Machine Learning with Go, but what about turning the tables for once? What can Machine Learning do *for* Go?

In this talk we will discover how different Machine Learning models can help us write better Go by predicting from our next character to our next bug!

**Description**:

Machine Learning is definitely what the cool kids are doing nowadays. Many wonder how to implement simple Machine Learning models, such as [image recognition](https://outcrawl.com/image-recognition-api-go-tensorflow/), and many frameworks are popping out such as [Tensorflow for Go](https://godoc.org/github.com/tensorflow/tensorflow/tensorflow/go), [GoLearn](https://github.com/sjwhitworth/golearn), or [Gorgonia](https://github.com/gorgonia/gorgonia).

What not many are talking about is how to those techniques to improve our developer routines. Machine Learning on Source Code (MLonCode) is a very interesting field because it is at the frontier of [Natural Language Processing](https://en.wikipedia.org/wiki/Natural-language_processing), [Graph-Based Machine Learning](https://research.googleblog.com/2016/10/graph-powered-machine-learning-at-google.html), Static Analysis, and has the potential to impact other fields like Dynamic Analysis of programs.

The amount of data available for this problem is almost overwhelming, and given that data is the fuel of Machine Learning, we are excited for an amazing ride!

This talk will cover the basics of what Machine Learning techniques can be applied to source code, specifically we will discover:

- [embeddings over identifiers](https://blog.sourced.tech/post/id2vec/),
- structural embeddings over source code, answering the question how similar are two fragments of code,
- recurrent neural networks for code completion,
- future direction of the research.

While the topic is advanced, the level of mathematics required for this talk will be kept to a minimum.
Rather than getting stuck in the details, we'll discuss the advantages and limitations of these techniques, and their possible implications to our developer lives.

**Notes**:

WARNING: the notes below are not anonymous

I have a very deep knowledge of Go after working in the Go team for over 6 years, and since I joined [source{d}](https://sourced.tech) back in November I've been immersed in the world of Machine Learning.
The mix makes for a very exciting field that I have a passion for and I'm looking forward to sharing it on stage.

I've given many talks at large Go conferences (and others) such as an opening keynote at GopherCon, many talks at Google I/O, etc.
In addition to this I regularly release Go related videos on [justforfunc](http://justforfunc.com) which can give you an idea of my presentation style.
