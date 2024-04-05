# Task-name

### Paper

Title: `HotpotQA: A Dataset for Diverse, Explainable Multi-hop Question Answering`

Abstract: https://arxiv.org/abs/1809.09600

Existing question answering (QA) datasets fail to train QA systems to perform complex reasoning and provide explanations for answers. We introduce HotpotQA, a new dataset with 113k Wikipedia-based question-answer pairs with four key features: (1) the questions require finding and reasoning over multiple supporting documents to answer; (2) the questions are diverse and not constrained to any pre-existing knowledge bases or knowledge schemas; (3) we provide sentence-level supporting facts required for reasoning, allowing QA systems to reason with strong supervision and explain the predictions; (4) we offer a new type of factoid comparison questions to test QA systems' ability to extract relevant facts and perform necessary comparison. We show that HotpotQA is challenging for the latest QA systems, and the supporting facts enable models to improve performance and make explainable predictions.

Homepage: https://hotpotqa.github.io/ 

HuggingFace dataset: https://huggingface.co/datasets/hotpot_qa


### Citation

```
@misc{yang2018hotpotqa,
      title={HotpotQA: A Dataset for Diverse, Explainable Multi-hop Question Answering}, 
      author={Zhilin Yang and Peng Qi and Saizheng Zhang and Yoshua Bengio and William W. Cohen and Ruslan Salakhutdinov and Christopher D. Manning},
      year={2018},
      eprint={1809.09600},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```

### Groups and Tasks

#### Groups

- Not part of a group yet

#### Tasks

* `hotpotqa`: `1-sentence description of what this particular task does`

### Checklist

For adding novel benchmarks/datasets to the library:
* [x] Is the task an existing benchmark in the literature?
  * [x] Have you referenced the original paper that introduced the task?
  * [ ] If yes, does the original paper provide a reference implementation? If so, have you checked against the reference implementation and documented how to run such a test?


If other tasks on this dataset are already supported:
* [ ] Is the "Main" variant of this task clearly denoted?
* [ ] Have you provided a short sentence in a README on what each new variant adds / evaluates?
* [ ] Have you noted which, if any, published evaluation setups are matched by this variant?
