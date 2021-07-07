# Sundanese OSCAR, mC4, CC100, Wiki Corpus

Sundanese Corpus tokenized using `BertWordPieceTokenizer`. Sequence maximum length set to `128`.

## Usage

### Download & Unzip File

```
!wget -q https://github.com/w11wo/nlp-datasets/raw/main/sundanese-corpus/bwp-tokenized-su-oscar-mc4-cc100-wiki.zip
!unzip -q /content/bwp-tokenized-su-oscar-mc4-cc100-wiki.zip
```

### Load Tokenized Dataset

```python
from datasets import load_from_disk
tokenized_datasets = load_from_disk(f"bwp-tokenized-su-oscar-mc4-cc100-wiki")
>> DatasetDict({
    train: Dataset({
        features: ['attention_mask', 'input_ids', 'special_tokens_mask', 'token_type_ids'],
        num_rows: 861057
    })
    test: Dataset({
        features: ['attention_mask', 'input_ids', 'special_tokens_mask', 'token_type_ids'],
        num_rows: 93593
    })
})
```
