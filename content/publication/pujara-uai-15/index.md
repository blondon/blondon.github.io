---
title: "Budgeted Online Collective Inference"
date: 2015-01-01
publishDate: 2020-01-17T19:49:07.321055Z
authors: ["Jay Pujara", "Ben London", "Lise Getoor"]
publication_types: ["1"]
abstract: "<p>Updating inference in response to new evidence is a fundamental challenge in artificial intelligence. Many real problems require large probabilistic graphical models, containing millions of interdependent variables. For such large models, jointly updating the most likely (i.e., MAP) configuration of the variables each time new evidence is encountered can be infeasible, even if inference is tractable. In this paper, we introduce budgeted online collective inference, in which the MAP configuration of a graphical model is updated efficiently by revising the assignments to a subset of the variables while holding others fixed. The goal is to selectively update certain variables without sacrificing quality with respect to full inference. To formalize the consequences of partially updating inference, we introduce the concept of inference regret. We derive inference regret bounds for a class of graphical models with strongly-convex free energies. These theoretical insights, combined with a thorough analysis of the optimization solver, motivate new approximate methods for efficiently updating the variable assignments under a budget constraint. In experiments, we demonstrate that our algorithms can reduce inference time by 65% with accuracy comparable to full inference.</p>"
featured: false
publication: "*Uncertainty in Artificial Intelligence*"
---

