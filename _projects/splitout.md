---
title: 'SplitOut: Code Repository of Paper'
date: 2023-11-04
link: https://github.com/ege-erdogan/splitout
tags:
  - pytorch
  - matplotlib
  - numpy
  - scikitlearn
  - pandas
---

Split learning enables efficient and privacy-aware training of a deep neural network by splitting a neural network so that the clients (data holders) compute the first layers and only share the intermediate output with the central compute-heavy server. This paradigm introduces a new attack medium in which the server has full control over what the client models learn, which has already been exploited to infer the private data of clients and to implement backdoors in the client models. Although previous work has shown that clients can successfully detect such training-hijacking attacks, the proposed methods rely on heuristics, require tuning of many hyperparameters, and do not fully utilize the clients' capabilities. In this work, we show that given modest assumptions regarding the clients' compute capabilities, an out-of-the-box outlier detection method can be used to detect existing training-hijacking attacks with almost-zero false positive rates. We conclude through experiments on different tasks that the simplicity of our approach we name SplitOut makes it a more viable and reliable alternative compared to the earlier detection methods.

[Github Repo](https://github.com/ege-erdogan/splitout)
[Paper (CANS Version)](https://doi.org/10.1007/978-981-97-8016-7_6)
