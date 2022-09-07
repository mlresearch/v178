---
title: 'Open Problem: Running time complexity of accelerated $\ell_1$-regularized PageRank'
abstract: 'The results in Google Search, Twitter and other popular search engines traditionally utilize the Personalized PageRank (PPR) vector to rank the results in their search engines. Additionally, there is a plethora of applications beyond the web~\citep{G15} which are modelled using PPR. In recent work by~\cite{ACL06,GM14_ICML,fountoulakis2019variational}, it was shown that small probabilities in PPR vector, e.g., web pages beyond the first page in Google Search, can be thresholded out automatically by utilizing $\ell_1$-regularization or equivalently by early termination. Both versions result in approximate computation of PPR. The current fastest method for computing the $\ell_1$-regularized PPR uses proximal gradient method and requires $\tilde{\mathcal{O}}((\alpha \rho)^{-1})$ total running time, where $\alpha$ is the teleportation parameter and $\rho$ is a parameter which controls the level of sparsity in the $\ell_1$-regularized PPR. It is important to note that the running time complexity does not depend on the size of the underlying graph (e.g. the length of the PPR vector). Such property has become a prerequisite to probe modern large scale networks. A seemingly natural way to build an even faster algorithm for computing the $\ell_1$-regularized PPR is to accelerate the proximal gradient method and consequently reduce the running time complexity to $\tilde{\mathcal{O}}((\sqrt{\alpha} \rho)^{-1})$. This will lead to a speed-up by a factor of $1/\sqrt{\alpha}$ and improve the running time of various network analytic methods which build upon PPR. However, the original analysis of the proximal gradient method in~\cite{fountoulakis2019variational} does not apply to the accelerated version. While we have empirical evidence that indicates accelerated proximal gradient requires less total running time, it is not even clear if acceleration could lead to a worse running time complexity in the worst case.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 5630-5632
id: open-problem-fountoulakis22a
month: 0
tex_title: 'Open Problem: Running time complexity of accelerated $\ell_1$-regularized PageRank'
firstpage: 5630
lastpage: 5632
page: 5630-5632
order: 5630
cycles: false
bibtex_author: Fountoulakis, Kimon and Yang, Shenghao
author:
- given: Kimon
  family: Fountoulakis
- given: Shenghao
  family: Yang
date: 2022-09-01
address:
container-title: Proceedings of Thirty Fifth Conference on Learning Theory
volume: '178'
genre: inproceedings
issued:
  date-parts:
  - 2022
  - 9
  - 1
pdf: https://proceedings.mlr.press/v178/open-problem-fountoulakis22a/open-problem-fountoulakis22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
