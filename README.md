# CSValues: Automatic Detection of Research Values from Scientific Abstracts Across Computer Science Subfields

This repository contains the datasets and codebook used in our extended abstract "Automatic Detection of Research Values from Scientific Abstracts Across Computer Science Subfields", presented at the 3rd International Conference of Science of Science & Innovation (2024).

## Overview

We present a value framework for analyzing research values expressed in computer science papers. Through iterative qualitative coding, we identified 10 key research values that commonly appear in CS research:

1. Performance
2. Novelty 
3. Efficiency
4. Generalizability
5. Understanding (Phenomenon Understanding & Theoretical Grounding)
6. Simplicity
7. Fairness (Fairness, Bias, Privacy & Ethics)
8. Society (Societal Implications)
9. Openness (Openness, Reproducibility, Collaboration & Future Work)
10. Usability

## Data

The repository contains both raw and annotated datasets:

### Raw Data
- `data/raw/1032-instances.json`: Contains 1032 sentences randomly sampled from CS paper abstracts, including paper metadata (ID, title, sampled sentence). Due to legal concerns, we do not include the abstract in the dataset. Users can fetch the abstract with the paper ID from the original dataset with Semantic Scholar API.

### Annotated Data
- `data/annotations/train.json`: Training set (40% of annotated data)
- `data/annotations/validation.json`: Validation set (30%)
- `data/annotations/test.json`: Test set (30%)

The annotation codebook and detailed descriptions of each research value can be found in `data/annotations/README.md`.

## Data Collection

The sentences were sampled from 226,600 papers published between 2013-2022 across 86 popular CS venues. Our sampling process:
1. Selected 86 popular CS research venues (consulted csrankings.org and 17 doctoral researchers)
2. Randomly sampled 12 abstracts from each venue
3. Randomly selected one sentence from each abstract
4. Two authors annotated the sentences through multiple rounds of discussion

## Citation

If you use this dataset in your research, please cite our paper:

```bibtex
@article{jiang2024researchvalues,
 title={Automatic Detection of Research Values from Scientific Abstracts Across Computer Science Subfields},
 author={Jiang, Hang and August, Tal and Soldaini, Luca and Lo, Kyle and Antoniak, Maria},
 note={Presented at The 3rd International Conference on the Science of Science and Innovation (ICSSI)},
 year={2024},
}
```

## License

This work is licensed under an Open Data Commons Attribution License (ODC-By) v1.0.

## Contact

For questions about the data or paper, please contact Hang Jiang (hjian42@icloud.com) and Maria Antoniak (maria.antoniak@colorado.edu).
