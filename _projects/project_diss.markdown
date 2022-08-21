---
layout: page
title: Dissertation
description: Referenceless Evaluation of NLG
img: /assets/img/colingslide.png
importance: 1
category: work
---

My PhD dissertation is [Referenceless Evaluation of Natural Language Generation from Meaning Representations](https://repository.library.georgetown.edu/handle/10822/1063073). I defended it in June 2021. 

The main contributions are also published in two conference papers:
* [A Human Evaluation of AMR-to-English Generation Systems](https://www.aclweb.org/anthology/2020.coling-main.420), COLING 2020
* [Referenceless Parsing-Based Evaluation of AMR-to-English Generation](https://aclanthology.org/2021.eval4nlp-1.12/), Eval4NLP Workshop 2021

Along the way I also did some relevant non-archival presentations:
* A Rule-Based and Statistical Approach to AMR Generation, [MASC-SLL 2018](https://sites.google.com/site/studentcolloquiumsll/2018)
* Referenceless Evaluation of Natural Language Generation from Meaning Representations, [MASC-SLL 2020](http://www.mascsll.org/2020/)
* Evaluating AMR-to-English NLG Evaluation, [EvalNLGEval 2020](https://evalnlg-workshop.github.io/)

---

Abstract:

> Automatic evaluation of NLG usually involves comparison to human-authored references which are treated as the ground truth. However, these references often fail to adequately capture the range of valid output for an NLG task, and many validation studies have shown that reference-based metrics do not reliably correlate well with human judgments. Focusing on the generation of English text from Abstract Meaning Representation (AMR), I explore referenceless approaches to evaluation, including both human and automatic methods.
 
> First, I conduct a new human evaluation study comparing five different AMR-to-English generation systems. Human annotators give numerical judgments for fluency and adequacy, as well as broad error type annotations. I discuss the relative quality of these systems and how these results compare to those of automatic metrics, finding that while the metrics are mostly successful in ranking systems overall, collecting human judgments allows for more nuanced comparisons. I also perform a qualitative analysis of common errors made by these systems.
 
> Next, I explore the possibility of automatically evaluating AMR-to-English generation by comparing a parse of the generated sentence to the input. I find that the quality of AMR parsers substantially impacts the performance of this approach, and that even with a state-of-the-art parser, the resulting metric underperforms popular reference-based metrics. However, when automatic parses are manually edited for accuracy, this evaluation approach improves greatly, outperforming most fully-automatic metrics and approaching the quality of a state-of-the-art learned metric. These results indicate that fully-automatic parser-based metrics are likely to prove more reliable in the future as the state of the art in AMR parsing continues to improve.
