# Speech-Emotion-Detecgtion
This Repository is meant to contain the Emotion Detection Techniques from speech signals. The work is done by Information Technology University, Lahore research staff under the supervision of Dr. Mudassir Shabbir.

### 1D and 2D Speech Emotion Recognition

Speech Emotion Recognition using raw speech signals from the EmoDB database using 1D and 2D CNN-LSTM architecture as given in the following paper.

Zhao, Jianfeng, Xia Mao, and Lijiang Chen. "Speech emotion recognition using deep 1D & 2D CNN LSTM networks." Biomedical Signal Processing and Control 47 (2019): 312-323.

EmoDB database can be downloaded from the following website

http://www.emodb.bilderbar.info/download/

There are 7 emotional classes and the validation accuracy obtained is ~78% for 2D CNN-LSTM using log-mel spectrogram of 8s of audio signals as input feature.
The maximum validation accuracy obtained for audio signals of 1s of length with 1D CNN-LSTM is around ~64%.

Developed and tested on the following:

Python 3.6 keras 2.3.1 Librosa 0.6.3

Help taken for 1D CNN-LSTM from [here](https://github.com/vandana-rajan/1D-Speech-Emotion-Recognition)

### Cross Lingual Experiments

A few cross lingual experiments are also done on Berlin Emodb German dataset, Italian Emovo dataset ([Paper](https://art.torvergata.it/handle/2108/97109)) and Urdu dataset ([Paper](https://arxiv.org/pdf/1812.10411.pdf)) on the same Deep Learning Model Architecture. 
Experiments shows that the combinations of datasets from two different languages can better help classification than the samples from same languages.
