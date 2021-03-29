# pytorch-Sentiment-classifier-using-RNN-LSTM
Sentiment classifier using RNN, LSTM from scratch

## Environment setting
### python 3.x
### pytorch 1.x


## Download training data

### clone Github repository
```python
!git clone https://github.com/nyu-mll/GLUE-baselines.git
```

### Download SST-2 only
```python
%cd GLUE-baselines/
!python download_glue_data.py --data_dir glue_data --tasks SST
```

### check the downloaded data
```python
!head -10 glue_data/SST-2/train.tsv
```

This Repository consists of basic RNN, basic LSTM, 2-layer and bidirectional LSTM models not used pytorch built in module, nn.RNN and nn.LSTM.
