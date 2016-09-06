# LSTM over tree structure
inspired by Recursive Neural Networks by [\[Socher 2012\]][1] [\[Socher 2013\]][2], 
[\[Zhu et al 2016\]][3] proposed LSTM over tree structures called _S-LSTM_ to solve 
semantic composition problem. [Zhu][3] used the same data input as [Socher][1], 
which requires syntactical tree to be present in the input. 
[\[Munkhdalai et al 2016\]][4] 
proposed a construct called _Neural Tree Indexers_ which allows the direct use 
of natural language itself.

## S-LSTM


[Reference links]: <>

[1]: http://nlp.stanford.edu/pubs/SocherHuvalManningNg_EMNLP2012.pdf "Semantic Compositionality through Recursive Matrix-Vector Spaces"
[2]: http://nlp.stanford.edu/~socherr/EMNLP2013_RNTN.pdf "Recursive Deep Models for Semantic Compositionality Over a Sentiment Treebank"
[3]: https://arxiv.org/pdf/1503.04881.pdf "Long Short-Term Memory Over Tree Structures"
[4]: https://arxiv.org/pdf/1607.04492v1.pdf "Neural Tree Indexers for Text Understanding"