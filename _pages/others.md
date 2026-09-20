---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

# Journal & Conference Papers
\* indicates equal contribution.

1. **Zhao Li**, Xin Wang, Jun Zhao, Wenbin Guo, Jianxin Li. HyCubE: Efficient Knowledge Hypergraph 3D Circular Convolutional Embedding [J]. IEEE Transactions on Knowledge and Data Engineering (IEEE TKDE), 37(4): 1902-1914, 2025. **(CCF-A, SCI-1)** [[Paper](https://ieeexplore.ieee.org/abstract/document/10845179)]
2. **Zhao Li**, Xin Wang, Zhao Jun, Feng Feng, Zirui Chen, Jianxin Li. HySAE: An Efficient Semantic-Enhanced Representation Learning Model for Knowledge Hypergraph Link Prediction [C]. In Proceedings of the ACM Web Conference 2025 (WWW 2025). 2025: 86-97. **(CCF-A, Oral)** [[Paper](https://dl.acm.org/doi/abs/10.1145/3696410.3714549)]
3. **Zhao Li**, Chenxu Wang, Xin Wang, Zirui Chen, Jianxin Li. HJE: Joint Convolutional Representation Learning for Knowledge Hypergraph Completion [J]. IEEE Transactions on Knowledge and Data Engineering (IEEE TKDE), 36(8): 3879-3892, 2024. **(CCF-A, SCI-1)** [[Paper](https://ieeexplore.ieee.org/abstract/document/10436025)]
4. **Zhao Li**, Xin Wang, Jianxin Li, Qingpeng Zhang. Deep attributed network representation learning of complex coupling and interaction [J]. Knowledge-Based Systems (KBS), 2021, 212: 106618. **(SCI-1, Hot Paper, Highly Cited Paper)** [[Paper](https://doi.org/10.1016/j.knosys.2020.106618)]
5. Wenbin Guo \*, **Zhao Li** \*, Xin Wang, Zirui Chen, Jun Zhao, Jianxin Li, Ye Yuan. ConvD: Attention Enhanced Dynamic Convolutional Embeddings for Knowledge Graph Completion [J]. IEEE Transactions on Knowledge and Data Engineering (IEEE TKDE), 37(9): 5049-5062, 2025. **(CCF-A, SCI-1)** [[Paper](https://ieeexplore.ieee.org/abstract/document/11048442)]
6. Chenxu Wang \*, **Zhao Li** \*, Xin Wang, Zirui Chen. EnhancE: Enhanced Entity and Relation Embedding for Knowledge Hypergraph Link Prediction [C]. Companion Proceedings of the ACM Web Conference 2023 (WWW 2023). 2023: 115-118. **(CCF-A)** [[Paper](https://doi.org/10.1145/3543873.3587326)]
7. **Zhao Li**. Knowledge Hypergraph Reasoning Based on Representation Learning [C]. In Database Systems for Advanced Applications: 28th International Conference (DASFAA 2023). 2023: 743-747. **(CCF-B, PhD Consortium)** [[Paper](https://doi.org/10.1007/978-3-031-30678-5_66)]
8. **Zhao Li**, Xin Liu, Xin Wang, Pengkai Liu, and Yuxin Shen. TransO: a knowledge-driven representation learning method with ontology information constraints [J]. World Wide Web (WWWJ), 2023, 26(1): 297-319. **(CCF-B, SCI-3)** [[Paper](https://doi.org/10.1007/s11280-022-01016-3)]
9. Yuxin Shen \*, **Zhao Li** \*, Xin Wang, Jianxin Li, Xiaowang Zhang. Datatype-Aware Knowledge Graph Representation Learning in Hyperbolic Space [C]. In Proceedings of the 30th ACM International Conference on Information and Knowledge Management (CIKM 2021). 2021: 1630–1639. **(CCF-B)** [[Paper](https://doi.org/10.1145/3459637.3482421)]
10. **Zhao Li**, Xin Wang, Jianxin Li. Structural role enhanced attributed network embedding[C]// International Conference on Web Information Systems Engineering (WISE 2019). 2019: 568‑582. **(CCF‑C)**
11. Shaowei Zhang \*, **Zhao Li** \*, Xin Wang. TKGAT: Temporal Knowledge Graph Representation Learning Using Attention Network[C]// International Conference on Advanced Data Mining and Applications (ADMA 2023). 2023: 46‑61. **(CCF‑C)**
12. Chenxu Wang, Xin Wang, **Zhao Li**, Zirui Chen, and Jianxin Li. HyConvE: A Novel Embedding Model for Knowledge Hypergraph Link Prediction with Convolutional Neural Networks [C]. In Proceedings of the ACM Web Conference 2023 (WWW 2023). 2023: 188–198. **(CCF-A)** [[Paper](https://doi.org/10.1145/3543507.3583256)]
13. Fuxiang Zhang, Xin Wang, **Zhao Li**, Jianxin Li. TransRHS: A Representation Learning Method for Knowledge Graphs with Relation Hierarchical Structure [C]. In Proceedings of the 29th International Joint Conference on Artificial Intelligence (IJCAI 2020). 2020: 2987–2993. **(CCF-A)** [[Paper](https://dl.acm.org/doi/abs/10.5555/3491440.3491853)]
14. Xin Wang, Zirui Chen, Haofen Wang, Leong Hou U, **Zhao Li**, Wenbin Guo. Large Language Model Enhanced Knowledge Representation Learning: A Survey [J]. Data Science and Engineering, 2025: 1-24. **(SCI-1)** [[Paper](https://link.springer.com/article/10.1007/s41019-025-00285-y#citeas)]

# Standards
- [The IEEE Standard of Financial Knowledge Graphs (2807.2-2024)](https://ieeexplore.ieee.org/abstract/document/10577610), 2024 **（核心成员）**
- [The IEEE Standard of Scientific Knowledge Graphs (2807.4-2024)](https://ieeexplore.ieee.org/document/10883010), 2024 **（核心成员）**

# Patents
<!-- 已申请国家发明专利 4 项，可在此逐条补充，例如：
- 张三, **李钊**. 一种基于知识图谱的XXX方法. 中国发明专利, 申请号: 2024XXXXXX.X, 2024.
-->
- （待补充）已申请国家发明专利 4 项。

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
