# Self-upgrading servers with Docker

**Updates**:  https://github.com/src-d/conferences/issues/11

**Sent on**:  2018/01/18

**Status**:   proposed

**Author**:   Francesc Campoy

**Slides**:   TBD

**Proposal**: N/A

**Abstract**:

Discover how we implemented a server that doesn't require any downtime to be extended with new features. Babelfish (bblf.sh) is an open source project created at source{d} that provides language parsing for *any* programming language.
Each parser is written in its own language, so we can't just simply put everything in a binary.

So how does this work? We are able to update and upgrade the API server by running Moby inside of Moby (we need to go deeper!) and using the Docker hub as our repository for parsers.

In addition to this, each container image for parsers needs to follow some quite strict specifications: and in order to do so we build a set of images via Makefile and multi-stage builds. All in all creates an efficient system that although is architecturally complex provides a simple developer experience.

This talk covers all the juicy details of the architecture and the lessons we learned while developing it.