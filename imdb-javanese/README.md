---
annotations_creators:
- found
extended:
- original
language_creators:
- machine-generated
languages:
- jv
licenses:
- odbl-1.0
multilinguality:
- monolingual
size_categories:
- 10K<n<100K
source_datasets:
- original
task_categories:
- text-classification
task_ids:
- sentiment-classification
---

# Dataset Card for "imdb-javanese"

## Table of Contents

- [Dataset Description](#dataset-description)
  - [Dataset Summary](#dataset-summary)
  - [Supported Tasks](#supported-tasks-and-leaderboards)
  - [Languages](#languages)
- [Dataset Structure](#dataset-structure)
  - [Data Instances](#data-instances)
  - [Data Fields](#data-instances)
  - [Data Splits Sample Size](#data-instances-sample-size)
- [Dataset Creation](#dataset-creation)
  - [Curation Rationale](#curation-rationale)
  - [Source Data](#source-data)
  - [Annotations](#annotations)
  - [Personal and Sensitive Information](#personal-and-sensitive-information)
- [Considerations for Using the Data](#considerations-for-using-the-data)
  - [Social Impact of Dataset](#social-impact-of-dataset)
  - [Discussion of Biases](#discussion-of-biases)
  - [Other Known Limitations](#other-known-limitations)
- [Additional Information](#additional-information)
  - [Dataset Curators](#dataset-curators)
  - [Licensing Information](#licensing-information)
  - [Citation Information](#citation-information)

## Dataset Description

- **Homepage:** [Github](https://github.com/w11wo/javanese-nlp)
- **Repository:** [Github](https://github.com/w11wo/javanese-nlp)
- **Paper:** [Aclweb](http://www.aclweb.org/anthology/P11-1015)
- **Point of Contact:** [Wilson Wongso](https://github.com/w11wo)
- **Size of downloaded dataset files:** 17.0 MB
- **Size of the generated dataset:** 47.5 MB
- **Total amount of disk used:** 64.5 MB

### Dataset Summary

Large Movie Review Dataset translated to Javanese. This is a dataset for binary sentiment classification containing substantially more data than previous benchmark datasets. We provide a set of 25,000 highly polar movie reviews for training, and 25,000 for testing. There is additional unlabeled data for use as well. We translated the [original IMDB Dataset](https://huggingface.co/datasets/imdb) to Javanese using the multi-lingual MarianMT Transformer model from [`Helsinki-NLP/opus-mt-en-mul`](https://huggingface.co/Helsinki-NLP/opus-mt-en-mul).

### Supported Tasks and Leaderboards

[More Information Needed](https://github.com/huggingface/datasets/blob/master/CONTRIBUTING.md#how-to-contribute-to-the-dataset-cards)

### Languages

[More Information Needed](https://github.com/huggingface/datasets/blob/master/CONTRIBUTING.md#how-to-contribute-to-the-dataset-cards)

## Dataset Structure

We show detailed information for up to 5 configurations of the dataset.

### Data Instances

An example of `javanese_imdb_train.csv` looks as follows.

| label | text                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
|-------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1     | "Drama romantik sing digawÃ© karo direktur Martin Ritt kuwi ora dingertÃ¨ni, nanging ana momen-momen sing marahi karisma lintang Jane Fonda lan Robert De Niro (kelompok sing luar biasa). DhÃ¨wÃ¨kÃ© dadi randha sing ora isa mlaku, iso anu anyar lan anyar-inventor-- kowÃ© isa nganggep isinÃ©. Adapsi novel Pat Barker ""Union Street"" (yak titel sing apik!) arep dinggo-back-back it on bland, lan pendidikan film kuwi gampang, nanging isih nyenengkÃ©; a rosy-hued-inventor-fantasi. Ora ana sing ngganggu gambar sing sejati ding kok iso dinggo nggawe gambar sing paling nyeneng."       |
| 0     | "Pengalaman wong lanang sing nduwÃ© perasaan sing ora lumrah kanggo babi. Mulai nganggo tuladha sing luar biasa yaiku komedia. Wong orkestra termel digawÃ© dadi wong gila, sing kasar merga nyanyian nyanyi. SayangÃ©, kuwi tetep absurd wektu WHOLE tanpa ceramah umum sing mung digawÃ©. Malah, sing ana ing jaman kuwi kudu ditinggalkÃ©. Diyalog kryptik sing nggawÃ© Shakespeare marah gampang kanggo kelas telu. Pak teknis kuwi luwih apik timbang kowe mikir nganggo cinematografi sing apik sing jenengÃ© Vilmos Zsmond. Masa depan bintang Saly Kirkland lan Frederic Forrest isa ndelok." |

### Data Fields

- `text`: The movie review translated into Javanese.
- `label`: The sentiment exhibited in the review, either `1` (positive) or `0` (negative).

### Data Splits Sample Size

|train|unsupervised|test |
|----:|-----------:|----:|
|25000|       50000|25000|

## Dataset Creation

### Curation Rationale

[More Information Needed](https://github.com/huggingface/datasets/blob/master/CONTRIBUTING.md#how-to-contribute-to-the-dataset-cards)

### Source Data

#### Initial Data Collection and Normalization

[More Information Needed](https://github.com/huggingface/datasets/blob/master/CONTRIBUTING.md#how-to-contribute-to-the-dataset-cards)

#### Who are the source language producers?

[More Information Needed](https://github.com/huggingface/datasets/blob/master/CONTRIBUTING.md#how-to-contribute-to-the-dataset-cards)

### Annotations

#### Annotation process

[More Information Needed](https://github.com/huggingface/datasets/blob/master/CONTRIBUTING.md#how-to-contribute-to-the-dataset-cards)

#### Who are the annotators?

[More Information Needed](https://github.com/huggingface/datasets/blob/master/CONTRIBUTING.md#how-to-contribute-to-the-dataset-cards)

### Personal and Sensitive Information

[More Information Needed](https://github.com/huggingface/datasets/blob/master/CONTRIBUTING.md#how-to-contribute-to-the-dataset-cards)

## Considerations for Using the Data

### Social Impact of Dataset

[More Information Needed](https://github.com/huggingface/datasets/blob/master/CONTRIBUTING.md#how-to-contribute-to-the-dataset-cards)

### Discussion of Biases

[More Information Needed](https://github.com/huggingface/datasets/blob/master/CONTRIBUTING.md#how-to-contribute-to-the-dataset-cards)

### Other Known Limitations

[More Information Needed](https://github.com/huggingface/datasets/blob/master/CONTRIBUTING.md#how-to-contribute-to-the-dataset-cards)

## Additional Information

### Dataset Curators

[More Information Needed](https://github.com/huggingface/datasets/blob/master/CONTRIBUTING.md#how-to-contribute-to-the-dataset-cards)

### Licensing Information

[More Information Needed](https://github.com/huggingface/datasets/blob/master/CONTRIBUTING.md#how-to-contribute-to-the-dataset-cards)

### Citation Information

```
@InProceedings{maas-EtAl:2011:ACL-HLT2011,
  author    = {Maas, Andrew L.  and  Daly, Raymond E.  and  Pham, Peter T.  and  Huang, Dan  and  Ng, Andrew Y.  and  Potts, Christopher},
  title     = {Learning Word Vectors for Sentiment Analysis},
  booktitle = {Proceedings of the 49th Annual Meeting of the Association for Computational Linguistics: Human Language Technologies},
  month     = {June},
  year      = {2011},
  address   = {Portland, Oregon, USA},
  publisher = {Association for Computational Linguistics},
  pages     = {142--150},
  url       = {http://www.aclweb.org/anthology/P11-1015}
}

```
