# 每周论文

## 2019-11-01

1. [Estimating Position Bias without Intrusive Interventions](http://www.cs.cornell.edu/people/tj/publications/agarwal_etal_19a.pdf)

<details>
<summary>阅读笔记</summary>
<ol>
  <li>zzz：通过A/B实验，收集不同排序ranker下相同doc的点击差异数据，作为训练集</li>
  <li>andrew：利用该训练集中的position pair对（k^',k）来推算出每个位次上的浏览概率（examination probability）</li>
  <li>andrew：可能的用法，利用examination probability对排序完的排序做一次rerank</li>
  <li>eaton：求解的方式上，引入rkk'辅助求解每个位置的曝光概率pk，绕过了对单个r(q,d)的统计过程[相比EM算法那篇] </li>
</ol>
</details>


## 2019-11-15

1. [Balancing exploration and exploitation in listwise and pairwise online learning to rank for information retrieval](https://rd.springer.com/content/pdf/10.1007%2Fs10791-012-9197-9.pdf)

<details>
<summary>阅读笔记</summary>
<ol>
  <li></li>
</ol>
</details>


