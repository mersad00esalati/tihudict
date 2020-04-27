# Tihu Persian Dictionary

Tihu-dict is a pronouncing dictionary of Persian, suitable for uses in speech technology.

## Running G2P

This repository has a pre-trained model in Persian Language for [Sequence-to-Sequence G2P toolkit](https://github.com/cmusphinx/g2p-seq2seq). Please check the release page to download pre-trained models.
Unpack the model after download. The model is trained on [Tihu dictionary](./tihu.demo.dict).

```
wget -O g2p-seq2seq-tihudict.tar.gz https://github.com/tihu-nlp/tihudict/releases/download/v2.0/g2p-seq2seq-tihudict-model-2.0.tar.gz
tar xf g2p-seq2seq-tihudict.tar.gz
```

The easiest way to check how the tool works is to run it the interactive mode and type the words

```
$ g2p-seq2seq --interactive --model_dir model_folder_path
...
> سلام
...
Pronunciations: [s a l A m]
...
>
```

### Word Error rate
WER: 0.136, Accuracy: 0.864

## License
Tihu is published under GNU General Public License. You may freely use, reproduce, modify or distribute it. If you think lilak is useful please support it.

