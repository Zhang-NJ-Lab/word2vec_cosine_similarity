# word2vec_cosine_similarity

*通过word2vec对英文摘要建模，输出和目标值（bandgap、formation energy...）最相关的3000个词排名

Sciences.txt :原始数据，英文摘要

results.txt :自定义分词后的文件

userdict2.txt :自定义词典

model.txt 文件：经过word2vec建立好的模型，可在百度网盘自行下载

链接：https://pan.baidu.com/s/1rdxII3C_94T5CcMM210sLw 

提取码：1111 

200,000 paper abstracts belonging to the physics, chemistry and materials science domains, which are downloaded from ScienceDirect published in the years from 2000 to 2020. The preprocessing step includes tokenization, customized dictionary, stop words, part-of-speech tagging (pos), lemmatization and uppercase/lowercase unification. The NLTK toolkit is employed for the tokenization, which results in the word segmentation that divides the sentences into a list of single words. The custom dictionaries mainly consist of phrases describing the descriptors and the target outputs, such as formation energy, band gap, etc. word2vec model construction process, the skip-gram method (the hyperparameters are: vector_size = 100, window = 10, sg = 1, sample = 10􀀀 3, epochs = 5) is selected because of the improved model accuracies than the Continuous Bag-of-Words (CBOW) counterpart [52], and the cosine similarity between the representative descriptors and the target output is calculated based on the word vectors.

