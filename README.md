# NLP Datasets

A collection of various NLP datasets, mainly Indonesia-related languages. These datasets are split into two: pre-training corpora and fine-tuning datasets.

---

# Table of Contents

- [Pre-training Corpora](#pre-training-corpora)
  - [Javanese IMDb](#javanese-imdb)
  - [Javanese Wikipedia v1](#javanese-wikipedia-v1)
  - [Javanese Wikipedia v2](#javanese-wikipedia-v2)
  - [Sundanese Wikipedia](#sundanese-wikipedia)
  - [Minangkabau Wikipedia](#minangkabau-wikipedia)
  - [OSCAR](#oscar)
  - [CC-100 Monolingual](#cc-100-monolingual)
  - [The C4 Multilingual Dataset](#the-c4-multilingual-dataset)
- [Fine-tuning Datasets](#fine-tuning-datasets)
  - [Sundanese Twitter Dataset for Emotion Classification](#sundanese-twitter-dataset-for-emotion-classification)
- [To Be Added](#tba)

---

# Pre-training Corpora

## [Javanese IMDb](https://huggingface.co/datasets/w11wo/imdb-javanese)

> English IMDb movie review dataset translated to Javanese using multi-lingual MarianMT Transformer [`Helsinki-NLP/opus-mt-en-mul`](https://huggingface.co/Helsinki-NLP/opus-mt-en-mul).

Split (47.5 MB):

- 25,000 Train
- 25,000 Test
- 50,000 Unsupervised

---

## [Javanese Wikipedia v1](https://github.com/w11wo/nlp-datasets/tree/main/javanese-wikipedia-v1)

> Javanese Wikipedia documents from Wikidump. Collected on December 2020.

Split (319 MB):

- 80,067 Unsupervised

---

## [Javanese Wikipedia v2](https://github.com/w11wo/nlp-datasets/tree/main/javanese-wikipedia-v2)

> Javanese Wikipedia documents from Wikidump. Collected on June 2021.

Split (342 MB):

- 84,507 Unsupervised

---

## [Sundanese Wikipedia](https://github.com/w11wo/nlp-datasets/tree/main/sundanese-wikipedia)

> Sundanese Wikipedia documents from Wikidump. Collected on June 2021.

Split (279 MB):

- 68,920 Unsupervised

---

## [Minangkabau Wikipedia](https://github.com/w11wo/nlp-datasets/tree/main/minangkabau-wikipedia)

> Minangkabau Wikipedia documents from Wikidump. Collected on June 2021.

Split (911 MB):

- 229,869 Unsupervised

---

## [OSCAR\*](https://oscar-corpus.com/)

> "OSCAR or Open Super-large Crawled Aggregated coRpus is a huge multilingual corpus obtained by language classification and filtering of the Common Crawl corpus using the goclassy architecture."

Split^:

- Indonesian (16 GB)
- Javanese (583 KB)
- Sundanese (141 KB)
- Minangkabau (310 KB)

\*_external resource_

^_deduplicated_

---

## [CC-100 Monolingual\*](http://data.statmt.org/cc-100/)

> "This corpus comprises of monolingual data for 100+ languages [...] This was constructed using the urls and paragraph indices provided by the CC-Net repository by processing January-December 2018 Commoncrawl snapshots."

Split:

- Indonesian (36 GB)
- Javanese (37 MB)
- Sundanese (15 MB)

\*_external resource_

---

## [The C4 Multilingual Dataset\*](https://github.com/allenai/allennlp/discussions/5265)

> "A colossal, cleaned version of Common Crawl's web crawl corpus. Based on Common Crawl dataset."

Split:

- Indonesian (242 GB)
- Javanese (876 MB)
- Sundanese (464 MB)

\*_external resource_

---

# Fine-tuning Datasets

## [Sundanese Twitter Dataset for Emotion Classification\*](https://github.com/virgantara/sundanese-twitter-dataset)

> O. V. Putra, F. M. Wasmanson, T. Harmini, and S. N. Utama, “Sundanese twitter dataset for emotion classification,” virtual, Nov. 2020.

Split (235 KB):

- 2,518 Train
- 12 Test

\*_external resource_

---

# TBA

- Wikipedia documents from other regional languages

  - ~~Minangkabau~~ `min`
  - Banyumasan/Basa Banyumasan `map-bms`
  - Acehnese `ace`
  - Gorontalo/Bahasa Hulontalo `gor`
  - Balinese `ban`
  - Banjar `bjn`
  - Madurese `mad`
  - Toba Batak Language `bbc`

- Online news

  - [Solopos Jagad Jawa](https://www.solopos.com/jagad-jawa) (Javanese)
  - [BewaraJabar Warta Sunda](https://bewarajabar.com/category/warta-sunda/) (Sundanese)

- Classification Datasets
  - Indonesian
    - [Tweets Responding to the Indonesian Government’s Handling of COVID-19: Sentiment Analysis Using SVM with Normalized Poly Kernel](https://e-journal.unair.ac.id/JISEBI/article/view/19624)
  - Javanese
    - [Classification of Javanese Language Level on Article Using Multinomial Naive Bayes and N-Gram Methods](https://iopscience.iop.org/article/10.1088/1742-6596/1306/1/012049/pdf)
    - [Attention-based CNN-BiLSTM for dialect identification on Javanese text](https://kinetik.umm.ac.id/index.php/kinetik/article/view/1121)
  - Sundanese
    - [Analisis Sentiment Tweets Berbahasa Sunda Menggunakan Naive Bayes Classifier dengan Seleksi Feature Chi Squared Statistic](http://openjournal.unpam.ac.id/index.php/informatika/article/view/3186/pdf)
    - [Sundanese Language Level Detection Using Rule-Based Classification: Case Studies On Twitter](http://www.ijstr.org/final-print/aug2020/Sundanese-Language-Level-Detection-Using-Rule-based-Classification-Case-Studies-On-Twitter.pdf)
