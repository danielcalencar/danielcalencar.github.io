---
published: true
title: "Improving the Pull Requests Review Process Using Learning-to-rank Algorithms"
layout: post
authors: ["Guoliang Zhao", "Daniel Alencar da Costa and Ying Zou"]
preprint: https://github.com/danielcalencar/danielcalencar.github.io/raw/master/papers/EMSE2019-Guoliang.pdf 
venue: Empirical Software Engineering (EMSE) 
award: false
acmaward: false
category: [Journal Papers]
tags: [EMSE, 2019, Pull Requests, Learning to Rank]
---   

### Abstract 

Collaborative software development platforms (such as GitHub and GitLab) have
become increasingly popular as they have attracted thousands of external
contributors to contribute to open source projects. The external contributors
may submit their contributions via pull requests, which must be reviewed before
being integrated into the central repository. During the review process,
reviewers provide feedback to contributors, conduct tests and request further
modifications before finally accepting or rejecting the contributions. The role
of reviewers is key to maintain the effective review process of the project.
However, the number of decisions that reviewers can make is far superseded by
the increasing number of pull requests submissions. To help reviewers to
perform more decisions on pull requests within their limited working time, we
propose a learning-to-rank (LtR) approach to recommend pull requests that can
be quickly reviewed by reviewers. Different from a binary model for predicting
the decisions of pull requests, our ranking approach complements the existing
list of pull requests based on their likelihood of being quickly merged or
rejected. We use 18 metrics to build LtR models and we use six different LtR
algorithms, such as ListNet, RankNet, MART and random forest. We conduct
empirical studies on 74 Java projects to compare the performances of the six
LtR algorithms. We compare the best performing algorithm against two baselines
obtained from previous research regarding pull requests prioritization: the
first-in-and-first-out (FIFO) baseline and the small-size-first baseline. We
then conduct a survey with GitHub reviewers to understand the perception of
code reviewers regarding the usefulness of our approach. We observe that: (1)
The random forest LtR algorithm outperforms other five well adapted LtR
algorithms to rank quickly merged pull requests. (2) The random forest LtR
algorithm performs better than both the FIFO and the small-size-first
baselines, which means our LtR approach can help reviewers make more decisions
and improve their productivity. (3) The contributor’s social connections and
contributor’s experience are the most influential metrics to rank pull requests
that can be quickly merged. (4) The GitHub reviewers that participated in our
survey acknowledge that our approach complements existing prioritization
baselines to help them to prioritize and to review more pull requests.

### Bibtex 

{% highlight tex %}
@article{zhao2019improving,
  title={Improving the pull requests review process using learning-to-rank algorithms},
  author={Zhao, Guoliang and da Costa, Daniel Alencar and Zou, Ying},
  journal={Empirical Software Engineering},
  pages={1--31},
  year={2019},
  publisher={Springer}
}
{% endhighlight %}


