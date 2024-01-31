# Causality-oriented Trustworthy Recommender Systems (CTRS) project
This project collects several representative open-source CTRS algorithms and widely used datasets, providing additional online sources for the survey "**Trustworthy Recommender Systems: A Survey from A Causal Learning Perspective**".

## CTRS Open-source Algorithms
We organize and list a wide range of open-source CTRS algorithms in Table 1. The listed algorithms are carefully selected and can be used as baselines in future work.

<table>
  <tr>
    <th width="200px">Algorithm</th>
    <th>Challenge</th>
    <th>Causal solution</th>
    <th>Venue</th>
    <th>Paper</th>
    <th>Link</th>
  </tr>
  <tr>
    <td width="200px">[Li <i>et al.</i>, 2021]</td>
    <td>Attribute bias</td>
    <td>Counterfactual inference</td>
    <td>SIGIR'2021</td>
    <td>Towards personalized fairness based on causal notion</td>
    <td><a href="https://github.com/yunqi-li/Personalized-Counterfactual-Fairness-in-Recommendation">Link</a></td>
  </tr>
  <tr>
    <td>[Zhang <i>et al.</i>, 2021]</td>
    <td>Popularity bias</td>
    <td>Structure adjustment</td>
    <td>SIGIR'2021</td>
    <td>Causal intervention for leveraging popularity bias in recommendation</td>
    <td><a href="https://github.com/zyang1580/PDA">Link</a></td>
  </tr>
  <tr>
    <td>[Wei <i>et al.</i>, 2021]</td>
    <td>Popularity bias</td>
    <td>Counterfactual inference</td>
    <td>KDD'2021</td>
    <td>Model-agnostic counterfactual reasoning for eliminating popularity bias in recommender system</td>
    <td><a href="https://github.com/weitianxin/MACR">Link</a></td>
  </tr>
  <tr>
    <td>[Joachims <i>et al.</i>, 2018]</td>
    <td>Position bias</td>
    <td>Propensity reweighting</td>
    <td>WSDM'2017</td>
    <td>Unbiased learning-to-rank with biased feedback</td>
    <td><a href="https://github.com/ULTR-Community/ULTRA">Link</a></td>
  </tr>
  <tr>
    <td>[Li <i>et al.</i>, 2023]</td>
    <td>Selection bias</td>
    <td>Propensity reweighting</td>
    <td>WWW'2023</td>
    <td>Balancing unobserved confounding with a few unbiased ratings in debiased recommendations</td>
    <td><a href="https://github.com/haoxuanli-pku/WWW23-Balancing-Unobserved-Confounding">Link</a></td>
  </tr>
  <tr>
    <td>[Zheng <i>et al.</i>, 2021]</td>
    <td>Conformity bias</td>
    <td>Disentanglement</td>
    <td>WWW'2021</td>
    <td>Disentangling user interest and conformity for recommendation with causal embedding</td>
    <td><a href="https://github.com/tsinghua-fib-lab/DICE">Link</a></td>
  </tr>
  <tr>
    <td>[He <i>et al.</i>, 2023]</td>
    <td>Spurious correlations</td>
    <td>Structure adjustment</td>
    <td>TOIS'2023</td>
    <td>Addressing confounding feature issue for causal recommendation</td>
    <td><a href="https://github.com/zyang1580/DCR">Link</a></td>
  </tr>
  <tr>
    <td>[Mu <i>et al.</i>, 2022]</td>
    <td>Spurious correlations</td>
    <td>Counterfactual augmentation</td>
    <td>SIGIR'2022</td>
    <td>Alleviating spurious correlations in knowledgeaware recommendations through counterfactual generator</td>
    <td><a href="https://github.com/RUCAlBox/CGKR">Link</a></td>
  </tr>
  <tr>
    <td>[Zhang <i>et al.</i>, 2021]</td>
    <td>Noisy feedback</td>
    <td>Counterfactual augmentation</td>
    <td>SIGIR'2021</td>
    <td>Counterfactual reward modification for streaming recommendation with delayed feedback</td>
    <td><a href="https://github.com/hnjia00/Delayed-Feedback/">Link</a></td>
  </tr>
  <tr>
    <td>[Wang <i>et al.</i>, 2021]</td>
    <td>Bias amplification</td>
    <td>Structure adjustment</td>
    <td>KDD'2021</td>
    <td>Deconfounded recommendation for alleviating bias amplification</td>
    <td><a href="https://github.com/WenjieWWJ/DecRS">Link</a></td>
  </tr>
  <tr>
    <td>[Gao <i>et al.</i>, 2024]</td>
    <td>Filter bubble bias</td>
    <td>Counterfactual inference</td>
    <td>TOIS'2023</td>
    <td>CIRS: bursting filter bubbles by counterfactual interactive recommender system</td>
    <td><a href="https://github.com/chongminggao/CIRS-codes">Link</a></td>
  </tr>
  <tr>
    <td>[Wang <i>et al.</i>, 2022]</td>
    <td>Filter bubble bias</td>
    <td>Counterfactual inference</td>
    <td>SIGIR'2022</td>
    <td>User-controllable recommendation against filter bubbles</td>
    <td><a href="https://github.com/WenjieWWJ/UCRS">Link</a></td>
  </tr>
  <tr>
    <td>[Tan <i>et al.</i>, 2021]</td>
    <td>Unexplainable results</td>
    <td>Counterfactual inference</td>
    <td>CIKM'2021</td>
    <td>Counterfactual explainable recommendation</td>
    <td><a href="https://github.com/christjann/counter">Link</a></td>
  </tr>
  <tr>
    <td>[Ghazimatin <i>et al.</i>, 2020]</td>
    <td>Unexplainable results</td>
    <td>Counterfactual inference</td>
    <td>WSDM'2020</td>
    <td>PRINCE: provider-side interpretability with counterfactual explanations in recommender systems</td>
    <td><a href="https://github.com/azinmatin/prince/">Link</a></td>
  </tr>
  <tr>
    <td>[Xian <i>et al.</i>, 2019]</td>
    <td>Black-box mechanism</td>
    <td>Path discovery</td>
    <td>SIGIR'2019</td>
    <td>Reinforcement knowledge graph reasoning for explainable recommendation</td>
    <td><a href="https://github.com/orcax/PGPR">Link</a></td>
  </tr>
</table>
<p align="center"><b>Table 1.</b> A list of representative open-source CTRS algorithms.</p>

## Representative Datasets for CTRS
We also investigate the datasets commonly employed in CTRS studies. Apart from general recommendation datasets, e.g., the Douban Movie and the Netflix Prize dataset, we highlight several public datasets in Table 2. These datasets have been selected for their specific information, such as sensitive attributes, MAR ratings or users’ reviews, making them especially suitable for evaluating the trustworthiness of CTRS models. Moreover, RecSim, an open-source user-behavior simulation model, shows great help in simulating the environment with popularity bias.

<table>
  <tr>
    <th>Aspect</th>
    <th>Dataset</th>
    <th>Specific information</th>
    <th>#Interactions</th>
    <th>Reference</th>
    <th>Link</th>
  </tr>
  <tr>
    <td rowspan="2">Fairness</td>
    <td>MovieLens</td>
    <td>Sensitive attributes (e.g., gender)</td>
    <td>1,000,209</td>
    <td>Counterfactual explainable conversational recommendation</td>
    <td><a href="https://grouplens.org/datasets/movielens/">Link</a></td>
  </tr>
  <tr>
    <td>Insurance</td>
    <td>Sensitive attributes (e.g., marital status)</td>
    <td>5,382</td>
    <td>Towards personalized fairness based on causal notion</td>
    <td><a href="https://www.kaggle.com/datasets/mrmorj/insurance-recommendation">Link</a></td>
  </tr>
  <tr>
    <td rowspan="3">Robustness</td>
    <td>Coat</td>
    <td>Both MAR and MNAR ratings</td>
    <td>11,600</td>
    <td>Propensity matters: Measuring and enhancing balancing for recommendation</td>
    <td><a href="https://www.cs.cornell.edu/~schnabts/mnar/">Link</a></td>
  </tr>
  <tr>
    <td>Yahoo! R3</td>
    <td>Both MAR and MNAR ratings</td>
    <td>365,704</td>
    <td>Propensity matters: Measuring and enhancing balancing for recommendation</td>
    <td><a href="https://webscope.sandbox.yahoo.com/catalog.php?datatype=r&did=3">Link</a></td>
  </tr>
  <tr>
    <td>Taobao</td>
    <td>User positive feedback</td>
    <td>1,515,055</td>
    <td>Mitigating hidden confounding effects for causal recommendation</td>
    <td><a href="https://tianchi.aliyun.com/competition/entrance/231532/">Link</a></td>
  </tr>
  <tr>
    <td rowspan="3">Explainability</td>
    <td>Yelp</td>
    <td>Users’ reviews</td>
    <td>6,990,280</td>
    <td>Counterfactual explainable conversational recommendation</td>
    <td><a href="https://www.yelp.com/dataset/">Link</a></td>
  </tr>
  <tr>
    <td>Amazon</td>
    <td>Users’ reviews</td>
    <td>230,139,802</td>
    <td>Counterfactual explainable recommendation</td>
    <td><a href="https://nijianmo.github.io/amazon/">Link</a></td>
  </tr>
  <tr>
    <td>Goodreads</td>
    <td>Users’ reviews</td>
    <td>15,739,967</td>
    <td>PRINCE: provider-side interpretability with counterfactual explanations in recommender systems</td>
    <td><a href="https://mengtingwan.github.io/data/goodreads">Link</a></td>
  </tr>
</table>
<p align="center"><b>Table 2.</b> A list of public datasets commonly used for CTRS.</p>

