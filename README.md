# [Quebec Automobile Insurance Question-Answering With Retrieval-Augmented Generation]()

## About the Dataset

The dataset is composed of two components 1) the references corpus and 2) the Questions-Answering corpus (QnA).

### References Corpus
It contains Quebec legislatures and piece of automotive insurance references. For more details see our article.

### QnA Corpus
It contains a set of 82 automotive questions extracted from the Web. For more details see our article.

## To Cite

```bibtex
@inproceedings{beauchemin-etal-2024-quebec,
    title = "{Q}uebec Automobile Insurance Question-Answering With Retrieval-Augmented Generation",
    author = "Beauchemin, David  and
      Khoury, Richard  and
      Gagnon, Zachary",
    editor = "Aletras, Nikolaos  and
      Chalkidis, Ilias  and
      Barrett, Leslie  and
      Goan{\textcommabelow{t}}{\u{a}}, C{\u{a}}t{\u{a}}lina  and
      Preo{\textcommabelow{t}}iuc-Pietro, Daniel  and
      Spanakis, Gerasimos",
    booktitle = "Proceedings of the Natural Legal Language Processing Workshop 2024",
    month = nov,
    year = "2024",
    address = "Miami, FL, USA",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.nllp-1.5",
    pages = "48--60",
    abstract = "Large Language Models (LLMs) perform outstandingly in various downstream tasks, and the use of the Retrieval-Augmented Generation (RAG) architecture has been shown to improve performance for legal question answering (Nuruzzaman and Hussain, 2020; Louis et al., 2024). However, there are limited applications in insurance questions-answering, a specific type of legal document. This paper introduces two corpora: the Quebec Automobile Insurance Expertise Reference Corpus and a set of 82 Expert Answers to Layperson Automobile Insurance Questions. Our study leverages both corpora to automatically and manually assess a GPT4-o, a state-of-the-art (SOTA) LLM, to answer Quebec automobile insurance questions. Our results demonstrate that, on average, using our expertise reference corpus generates better responses on both automatic and manual evaluation metrics. However, they also highlight that LLM QA is unreliable enough for mass utilization in critical areas. Indeed, our results show that between 5{\%} to 13{\%} of answered questions include a false statement that could lead to customer misunderstanding.",
}
```
