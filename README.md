# TextClassification
Pytorch实现文本分类经典模型，TextCNN、TextRNN、TextRCNN、TextHAN（GRU+Attention）

并用于IMDB电影评论二分类任务中。

各模型在测试集上的准确率为：



**TextFNN:**
- TextFNN+GloVe Freeze: 77.22%
- TextFNN+GloVe UnFreeze: 84.84%
- TextFNN+Random: 49.90%

**TextCNN:**
- TextCNN+GloVe Freeze: 87.12%
- TextCNN+GloVe UnFreeze: 88.40%
- TextCNN+Random: 87.12%

**TextRNN:**
- TextRNN+LSTM+GloVe Freeze: 88.26%
- TextRNN+LSTM+GloVe UnFreeze: 88.15%
- TextRNN+LSTM+Random: 87.12%
- TextRNN+GRU+GloVe Freeze: 88.59%
- TextRNN+GRU+GloVe UnFreeze: 88.29%
- TextRNN+GRU+Random: 87.38%

**TextRCNN:**
- TextRCNN+GRU+GloVe UnFreeze: 89.80%

**TextHAN:**

- TextHAN+GRU+GloVe Unfreeze: 89.16%

