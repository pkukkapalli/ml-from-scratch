# ML from Scratch

This repo is for containing implementations of popular neural network models
that I implement from scratch (using PyTorch). This is mostly meant for
demonstration and learning purposes.

## Visual models

1. First, we start with the
   [Neocognitron (1980)](https://www.rctn.org/bruno/public/papers/Fukushima1980.pdf)
   which is a precursor to CNNs.
1. Then, we explore
   [LenNet (1989-1998)](http://vision.stanford.edu/cs598_spring07/papers/Lecun98.pdf)
1. (optional) We can explore
   [AlexNet (2012)](https://papers.nips.cc/paper/2012/file/c399862d3b9d6b76c8436e924a68c45b-Paper.pdf)
1. (optional) ZFNet (2013)
1. (optional) [VGGNet (2014)](https://arxiv.org/abs/1409.1556)
1. (optional) [GoogLeNet (2014)](https://arxiv.org/abs/1409.4842)
1. (optional) [ResNet (2015)](https://arxiv.org/abs/1512.03385)

## Language models

Much of this is source from
https://www.ruder.io/a-review-of-the-recent-history-of-nlp/.

1. Feed forward neural network for language modeling in
   [2001 by Bengio et al.](https://papers.nips.cc/paper_files/paper/2000/hash/728f206c2a01bf572b5940d7d9a8fa4c-Abstract.html)
1. Vanilla RNN from
   [1990](https://onlinelibrary.wiley.com/doi/abs/10.1207/s15516709cog1402_1).
1. RNN in
   [2010 by Mikolov et al.](https://www.semanticscholar.org/paper/Recurrent-neural-network-based-language-model-Mikolov-Karafi%C3%A1t/9819b600a828a57e1cde047bbe710d3446b30da5)
1. Original LSTM in
   [1997](https://deeplearning.cs.cmu.edu/F23/document/readings/LSTM.pdf)
1. LSTM in [2013 by Graves](https://arxiv.org/abs/1308.0850)
1. [word2vec in 2013](https://arxiv.org/abs/1301.3781). These type of embeddings
   are very general, and can be used for learning any sequence of things, not
   just words. You can also use it for unsupervised machine translation,
   especially for languages without very many resources.
1. Multi-task learning for NLP in
   [2008 by Collobert and Weston](https://www.semanticscholar.org/paper/A-unified-architecture-for-natural-language-deep-Collobert-Weston/57458bc1cffe5caa45a885af986d70f723f406b4).
   This is still widely used today for various purposes.
1. CNNs for NLP in [2014 by Kalchbrenner et al.](http://arxiv.org/abs/1404.2188)
1. CNNs and LSTMs combined in
   [2016 by Wang et al.](https://aclanthology.org/P16-2037/)
1. Recursive neural nets in
   [2013 by Socher et al.](https://aclanthology.org/D13-1170/)
1. Tree-based LSTMs in [2015 by Tai et al.](https://aclanthology.org/P15-1150/)
1. Graph Convolutional Encoders in
   [2017 by Bastings et al.](https://aclanthology.org/D17-1209/)
1. Sequence to sequence models in
   [2014 by Sutskever et al.](https://papers.nips.cc/paper_files/paper/2014/hash/a14ac55a4f27472c5d894ec1c3c743d2-Abstract.html).
   The encoder-decoder framework allows for learning how to decode any sort of
   representation. We can explore some like code analysis. As well as named
   entity recognition.
1. Attention in [2015 by Bahdanau et al.](https://arxiv.org/abs/1409.0473)
1. Transformer architecture in
   [2017 by Vaswani et al.](https://papers.nips.cc/paper_files/paper/2017/hash/3f5ee243547dee91fbd053c1c4a845aa-Abstract.html)
1. Look at the source article for multiple memory-based networks. We should try
   implementing some of them as well.
1. Fine-tuning large pretrained models. We should look at some papers that
   provide better context around to best do this.
1. Character-based neural networks for part of speech tagging and other things.
1. GANs for NLP
1. Reinforcement learning for NLP
