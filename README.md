# rsa-tutorials

This repository contains implementations of the Rational Speech Acts (RSA) framework [(Frank and Goodman, 2012)](http://langcog.stanford.edu/papers_new/frank-2012-science.pdf)
in Python.

While there are many great resources for learning about RSA (such as the [Probabilistic language understanding](www.problang.org) textbook), they are primarily written in WebPPL, 
which has a learning curve for those unfamiliar with PPLs. 
In the RSA framework, values can be computed by exact enumeration. Therefore, we don't strictly need the abstractions that make PPLs useful
(i.e. fast inference of posteriors), and can just use standard Python libraries to perform modeling.

`intro-to-rsa.ipynb` is a translation of Chapter 1 of the ProbLang textbook into Python that provides an implementation of the vanilla RSA model.

`continuous-incremental-rsa.ipynb` is an implementation of 2 variants of RSA: continuous RSA [(Degen et al. 2020)](http://alpslab.stanford.edu/papers/2020_DegenEtAl.pdf) 
and continuous incremental RSA [(Waldon and Degen 2021)](https://aclanthology.org/2021.scil-1.19.pdf).

If you're interested in contributing additional content, please reach out!
