# Replication Package for Establishing the Lifecycle of Technical Debt Items through both Source Code and Issue Trackers

##### Authors: Jie Tan, Daniel Feitosa, Paris Avgeriou

## Description of this study:

Although Technical Debt (TD) has gained more attention in recent years, most studies exploring TD are based on a single source (e.g., source code, code comments or issue trackers). Investigating information combined from different sources may yield insight that is more than the sum of its parts. In particular, we argue that exploring how TD items are managed in both issue trackers and software repositories (including source code and commit messages) can shed some light on what happens between the commits that incur TD and those that pay it back. To this end, we randomly selected 3,000 issues from the trackers of five projects, manually analyzed 200 issues that contained TD information, and identified and investigated the lifecycle of 219 TD items. The results indicate that most of the TD items marked as resolved in issue trackers are also paid back in source code, although many are not discussed after being identified in the issue tracker. Design Debt items are more likely to be paid back in source code, while Test Debt items are the least likely. We also learned that although TD items may be resolved a few days after being identified, it often takes a long time to be identified (around one year). In general, time is reduced if the same developer is involved in consecutive moments (i.e., introduction, identification, repayment decision-making and remediation), but the number of people involved in discussing the TD item does not seem to affect how quickly it is resolved.

## Structure of the replication package:

We created a technical debt dataset containing 3,000 issues from the trackers of five Apache open-source projects, each item is tagged as non-SATD or different types of SATD (technical-debt-issues-dataset.csv). Among those 3000 issues, we randomly selected 200 issues, matched them to the corresponding commits and then, we manually analyzed if each technical debt item was actually fixed in source code (manually-analyze-issues.csv). We also provided the detailed datasets to answer each reseach question. 

```
├── LICENSE
├── README.md
├── technical-debt-issues-dataset.csv
├── manually-analyze-issues.csv
├── RQ1-issues-fixed-introduced-commits.csv
├── RQ2-intervals.csv
├── RQ3-identification-latency.csv
├── RQ3-discussion-period.csv
├── RQ3-remediation-latency.csv
└── RQ3-remediation-latency-without-discussion.csv
```

## Paper

Latest version available on [arXiv](https://arxiv.org/abs/xxxxx)

If you publish a paper where this dataset helps your research, we encourage you to cite the following paper in your publication:

```

```

## Contact

- Please use the following email addresses if you have questions:
    - :email: <j.tanjie@outlook.com>
