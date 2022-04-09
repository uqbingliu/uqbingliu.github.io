---
title: "Effective and Privacy-preserving Federated Online Learning to Rank"
collection: publications
permalink: /publication/ictir2021-fdolr
excerpt: 'Best Student Paper Award'
date: 2021-07-11
venue: 'ICTIR'
authors: 'Shuyi Wang, <strong>Bing Liu</strong>, Shengyao Zhuang, Guido Zuccon'
track: 'Full Paper, &#x1F3C6 Best Student Paper Award'
pdf_url: "http://ielab.io/publications/pdfs/wang2021fpdgd.pdf"
code_url: "https://github.com/ielab/fpdgd-ictir2021"
---

## Abstract

Online Learning to Rank (OLTR) has been primarily studied in the
centralised setting, where a central server is responsible to index the
searchable data, collect the users’ queries and search interactions,
and optimize ranking models. A drawback of such a centralised
OLTR paradigm is that it cannot guarantee user’s privacy as all data
(both the searchable one and the one related to user interactions)
is collected by the server.
In this paper, we propose a Federated OLTR method, called
FPDGD, which leverages the state-of-the-art Pairwise Differentiable Gradient Descent (PDGD) and adapts it to the Federated
Averaging framework. For a strong privacy guarantee, we further
introduce a noise-adding clipping technique based on the theory of
differential privacy to be used in combination with FPDGD.
Empirical evaluation shows FPDGD significantly outperforms
the only other federated OLTR method. In addition, FPDGD is more
robust across different privacy guarantee requirements than the
current method: our method is therefore more reliable for real-life
applications.

