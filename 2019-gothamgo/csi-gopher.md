# CSI: Gopher

**Updates**:  https://github.com/src-d/conferences/issues/135

**Sent on**:  2019/01/19

**Status**:   accepted

**Author**:   Francesc Campoy and Matt Silverlock

**Slides**:   TBA

**Proposal**: N/A

**Abstract**:

## Elevator Pitch

You have 300 characters to sell your talk. This is known as the "elevator pitch". Make it as exciting and enticing as possible.

If we could intelligently parse all of the open-source Go code on GitHub, what could we learn? We're going to show you some of the interesting things we've found about Go projects in the wild, from library usage, idioms & package layouts to how Go library authors can use this data to make decisions about their own APIs.


## Description

You should make the description of your talk as compelling and exciting as possible. Remember, you're selling both the organizers of the events to select your talk, as well as trying to convince attendees your talk is the one they should see.

So you're the author of an open-source library, but it's grown organically over time, and you're thinking about improving the API, adopting new Go idioms, and maybe removing a few features that you feel add complexity. But how can you be sure that they aren't widely used? Is there a way you can precisely find and summarize how users (inc. other packages!) are consuming your APIs, down to the method? And armed with that data, what are the ways you could act on it?

Francesc & Matt are going to talk about:
How parsing code works - not with regex, but by building Abstract Syntax Trees (ASTs), as compilers do
How you can query that data across tens of thousands of repositories, and some of the interesting findings and statistics generated from it - including the most popular library functions, and an analysis of dependencies across projects
Misuse of APIs, and how library authors & the community-at-large can use tools like this to help others to both fix security bugs at scale, as well as understand where documentation and the APIs themselves are failing users
Adoption of frameworks and tooling (e.g. godep vs modules)
Security vulnerabilities (e.g. using math/rand for crypto, etc)
Dependency versioning, and helping users upgrade in a world of pinned versiond
The goal is for you to walk away with ideas on how you can analyze your own OSS projects, or even internal code, with something just a bit more powerful than the code search you might be used to!

**Notes**:

This field supports Markdown. Notes will only be seen by reviewers during the CFP process. This is where you should explain things such as technical requirements, why you're the best person to speak on this subject, etc…

This is a joint proposal & talk between Francesc Campoy (https://twitter.com/francesc) and Matt Silverlock (https://twitter.com/elithrar). This is inspired by a lot of the work Francesc is doing at source{d} on generating insights from code, as well as a talk Matt gave at a GoSF meetup on doing this the "bad" way with regex & SQL (https://github.com/elithrar/finding-bugs-with-bigquery).

Francesc's background includes substantial time on the Go team itself, significant community engagement, and experience parsing code in just this manner at his day job, which makes him particularly well equipped to give a talk like this. Matt is co-maintainer of several popular OSS libraries and has practical examples on how parsing OSS code can help maintainers make decisions about users consume OSS packages.

Critically, this talk is not a sales pitch for any particular product, and is focused on the how and why a Gopher might use tools like this.