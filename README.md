Supplementary materials for the paper **'Large Language Models Unpack Complex Political Opinions through Target-Stance Extraction.'  **
Includes the prompts used in benchmarks, the annotated stance-detection dataset, the annotator codebook, and the codebase.

'Codebook' includes the codebook used by the annotators.

**'Data'** includes four files:
- **test_main.csv** is the **_'gold test set'_** used in the benchmarks. It includes 200 annotated posts from r/NeutralPolitics, along with the titles of the submissions they were posted under. The labels for these posts were agreed upon in a blind annotation task by two annotators and further validated by an expert.
- **test_broad.csv** contains the same posts, with Target labels mapped to broader labels where necessary. Refer to the paper for details and the codebook for the mapping schema.
- **test_cf.csv** also includes the surrounding thread of the post being labeled, used in the Conversational Context technique.
- **all_labeled_posts.csv** includes 1,084 posts, each labeled by two annotators. This file includes posts where annotators did not reach agreement on target or stance labels, and can be used for further studies on learning from disagreement.

**'Labels'** includes the Targets provided to the models and their explanations, as described in the codebook, for both the default granular targets and the broader target labels.

**'Prompts'** includes all prompts tested in the paper, each corresponding to a different technique.

**'Scripts'** includes the batch creation, collection, and processing scripts used in this study. (WIP - please contact the maintainer if you need access.)


This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
