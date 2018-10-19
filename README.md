## BCWS: Bilingual Contextual Word Similarity Dataset

## Description
Every 4 lines in the file form a testing instance. The first line in the pos tag. The second and the third lines are the bilingual sentences. The target word in each sentence is indicated by <target\_word>. The fourth line is the annotated scores from 11 annotators and the average value. For more details, please refer to [[2]]().
Please note that we use Chinese(Traditional) in the dataset, which means the same with Chinese(Simplified) but with different form. This means if your training corpus or vocabulary is in Chinese(Simplified), we recommend you to use some conversion tool to first preprocess your data. For details, please refer to [[here]](https://github.com/MiuLab/CLUSE), we use [[this]](https://github.com/yichen0831/opencc-python) toolkit with *s2t* conversion mode.

## References
Please cite [[1]](https://arxiv.org/abs/1809.05694) and [[2]]() if you find the resources in this repository useful.

### CLUSE: Cross-Lingual Unsupervised Sense Embeddings

[1] Ta-Chung Chi and Yun-Nung Chen, [*CLUSE: Cross-Lingual Unsupervised Sense Embeddings*](https://arxiv.org/abs/1809.05694)

```
@inproceedings{chi-chen:2018:EMNLP2018,
  author    = {Chi, Ta-Chung  and  Chen, Yun-Nung},
  title     = {Cluse: Cross-lingual underspervised sense embeddings},
  booktitle = {Proceedings of the 2018 Conference on Empirical Methods in Natural Language Processing(EMNLP)},
  month     = {October},
  year      = {2018},
  address   = {Brussels, Belgium},
  publisher = {Association for Computational Linguistics},
}
```

### BCWS: Bilingual Contextual Word Similarity

[2] Ta-Chung Chi, Ching-Yen Shih and Yun-Nung Chen, [*BCWS: Bilingual Contextual Word Similarity*]()

```
@article{bcws,
  title={BCWS: Bilingual Contextual Word Similarity},
  author={Ta-Chung Chi, Ching-Yen Shih and Yun-Nung Che},
  journal={arXiv preprint arXiv:},
  year={2018}
}
```

