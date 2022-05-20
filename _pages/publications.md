---
layout: archive
title: "Publications"
permalink: /publications/
my_number: 5
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{https://scholar.google.com/citations?user=hy_oauIAAAAJ&hl=en}}">my Google Scholar profile</a>.</u>
{% endif %}

## Publications:

[1] **Cheng, L.**; Yang, Z.; Liao, B.; Hsieh, C.; Zhang, S. ODBO: Bayesian Optimization with prescreening for directed protein evolution. arXiv:2205.09548 (2022). [Link](https://arxiv.org/abs/2205.09548)

[2] **Cheng, L.**., Sun, J. & Miller III, T. F. Accurate molecular-orbital-based machine learning energies via unsupervised clustering of chemical space. arXiv:2204.09831 (2022). [Link](https://arxiv.org/abs/2204.09831)

[3] Sun, J.; **Cheng, L.**; Miller III, T.F. Molecular energy learning using alternative blackbox matrix-matrix multiplication (AltBBMM) algorithm for exact Gaussian process. arXiv:2109.09817 (2021). (Accepted for presentation at the NeurIPS 2021 AI for Science Workshop) [Link](https://openreview.net/pdf?id=lyJ9BRKUzms)

[4] DiRisio, R. J.<sup>\*</sup>; **Cheng, L.**<sup>\*</sup>; Finney, J. M.; Boyer, M. A.; Lu, F.; Moonkaen, P.; Sun, J.; Lee, S. J. R.; Deustua, J. E.; Miller III, T. F.; McCoy, A. B. Near ab initio potential energy surfaces for diffusion monte carlo using machine learning. In submission to *J. Phys. Chem. A*, **2022**. (*co-first author)

[5] Husch, T.; Sun, J.; **Cheng, L.**; Lee, S. J. R.; Miller III, T.F. Improved accuracy and transferability of molecular-orbital-based machine learning: Organics, transition-metal complexes, non-covalent interactions, and transition states. *J. Chem. Phys.*, **2021**. [Link](https://aip.scitation.org/doi/abs/10.1063/5.0032362)

[6] **Cheng, L.**; Kovachki, N; Welborn, M.; Miller III, T. F. Regression clustering for improved accuracy and training costs with molecular-orbital-based machine learning. *J. Chem. Theory Comput.*, **2019**. [Link](https://pubs.acs.org/doi/abs/10.1021/acs.jctc.9b00884)

[7] **Cheng, L.**; Welborn, M.; Miller III, T. F. A universal density matrix functional from molecular orbital-based machine learning: Transferability across organic molecules. *J. Chem. Phys.*, **2019**. [Link](https://pubs.acs.org/doi/abs/10.1021/acs.jctc.8b00636)

[8] Welborn, M.; **Cheng, L.**; Miller III, T. F. Transferability in machine learning for electronic structure via the molecular orbital basis. *J. Chem. Theory Comput.*, **2018**.[Link](https://aip.scitation.org/doi/full/10.1063/1.5088393) (Highlighted with commentary in [C&EN](https://cen.acs.org/physical-chemistry/computational-chemistry/Machine-learning-predicts-electronic-properties/96/web/2018/08) and [Caltech News](http://www.caltech.edu/news/researchers-put-ai-work-making-chemistry-predictions-83357))

[9] Knowles, D. B.; Shkel, I. A.; Phan, N. M.; Sternke, M.; Lingeman, E.; Cheng, X.; **Cheng, L.**; O’Connor, K.; Record, M. T. Chemical interactions of polyethylene glycols (PEGs) and glycerol with protein functional groups: Applications to effects of PEG and glycerol on protein processes. *Biochemistry*, **2015**, 54 (22), 3528–3542. [Link](https://pubs.acs.org/doi/10.1021/acs.biochem.5b00246)

## In submission/preparation:

[1] Sun, J.; **Cheng, L.**; Miller III, T.F. Machine learning for dipole moments with scalable Gaussian process and derivative kernels with molecular-orbital-based representation. In preparation.

## Patent:

Miller III, T.F.; Welborn, M.; Cheng, L.; Husch, T.; Song, J.; Kovachiki, N.; Burov, D.; Teh, Y.S.; Anandkumar, A.; Ding, F.; Lee, S.J.R.; Qiao, Z.; Lale, A.S. Systems and methods for determining molecular structures with molecular-orbital-based features. U.S. Patent 16817489, 2020 [Link](https://patents.google.com/patent/US20200294630A1/en)
{% include base_path %}

{% for post in site.publications reversed %}
  {% include publication.html %}
{% endfor %}
