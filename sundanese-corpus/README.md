# Sundanese OSCAR, mC4, CC100, Wiki Corpus

Sundanese Corpus tokenized using `BertWordPieceTokenizer` and `ByteLevelBPETokenizer`. Sequence maximum length set to `128`.

## Example Usage

### Download & Unzip Files

```
!wget -q https://github.com/w11wo/nlp-datasets/raw/main/sundanese-corpus/bwp-tokenized-su-oscar-mc4-cc100-wiki.zip
!wget -q https://github.com/w11wo/nlp-datasets/raw/main/sundanese-corpus/bwp-tokenizer/tokenizer.json
!wget -q https://github.com/w11wo/nlp-datasets/raw/main/sundanese-corpus/bwp-tokenizer/config.json
!unzip -q /content/bwp-tokenized-su-oscar-mc4-cc100-wiki.zip
```

### Load Tokenizer Model

```python
from transformers import AutoTokenizer

model_dir = PATH/TO/tokenizer.json

tokenizer = AutoTokenizer.from_pretrained(model_dir)
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
