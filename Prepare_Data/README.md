### Build dataset from scratch
We have used the following repo (https://github.com/TheAlgorithms) as the dataset since the code is well written.

##### download source code
```
git clone https://github.com/TheAlgorithms/Python
git clone https://github.com/TheAlgorithms/Java
```

##### Move the cloned repo into `dataset/` directory and then on cmd

```
python convert.py --segment_len 256 --stride 20 --dev_size 0.2
```

This will create trainset named train.jsonl and devset named dev.jsonl under `source_code/json/`

