# JsonToConll
JsonToConll can transform [doccano](https://github.com/doccano/doccano) jsonl file to conll or crf format file.

# Usage
```
# json to conll
poetry run python jsontoformat.py ./data/admin_new.jsonl conll > ./data/dataset.conll

# json to crf format
poetry run python jsontoformat.py ./data/admin_new.jsonl crf > ./data/dataset.txt
```

