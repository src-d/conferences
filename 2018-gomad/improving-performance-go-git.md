# Improving performance of go-git

**Sent on**: 2018/03/21

**Status**:  accepted

**Author**:  Javi Fontán

**Slides**:  https://docs.google.com/presentation/d/1eP0RE4WhkigBEjTMGp8Y5510eWdZtfvf2fU8OmNq2vw/edit?usp=sharing

**Proposal**: https://www.meetup.com/go-mad/events/248693855/

**Abstract**:

go-git is a 100% Go libray used to interact with git repositories. Even if it already supports most of the functionality it still lags a bit in performance when compared with the git CLI or some other libraries. I'll explain some of the problems that we face when dealing with git repos and some examples of performance improvements done to the library.
