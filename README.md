## Fine-tuning-BERT-for-semantic-sentence-pairs-classification

Bidirectional Encoder Representation from Transformers (BERT) is designed to pretrain deep bidirectional representations from
unlabeled text by jointly conditioning on both left and right context in all layers and have achieved State-Of-Art results on many NLP tasks like Question Answering , Sentiment analysis/classification , language inference and much more .

The above project is to identify weather 2 sequences are semantically equivalent or not based on the labels provided as training . In the code we'll see how to transform both sequences into a format that BERT accepts by creating efficient custom input pipelines and preprocessing for BERT . Finally we will take a BERT model from tf_hub and fine tune it on our data based on original paper guides for fine tuning.

For indepth explanation see the original paper : https://arxiv.org/pdf/1810.04805.pdf

Checkout my blogpost for practical implementation of state-of-art BERT in tensorflow : https://ali-hassan.medium.com/bd4561af5249?source=friends_link&sk=3ea0abc53fbf1d222d3f725223455654

![iamge](https://www.revuze.it/wp-content/uploads/2020/06/3-reasons-why-bert-is-game-changer-in-NLP-1024x496.png)
