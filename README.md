# ANLP-Neural-MT-seq2seq

### Problem Statement
We have seen different architectures for Neural Machine Translation. Starting with simple
Seq2Seq network, and an improvement of this architecture by adding attention.
- We had seen Seq2Seq architecture in the paper [Sequence to Sequence Learning with
Neural Networks, Stuskever et al.](https://papers.nips.cc/paper/2014/file/a14ac55a4f27472c5d894ec1c3c743d2-Paper.pdf)
- Followed by how the concept of attention was introduced in Neural Machine translation
in the paper [Neural Machine Translation by Jointly Learning to Align and Translate,
Bhadnau et al.](https://arxiv.org/abs/1409.0473)
In this assignment, you have to code these two Neural Machine translation models and
train them on a simple parallel corpus, from English to Hindi.

### Dataset
- The language pair we are using is English - Hindi. If you are not familiar with this language
please reach out to use, we will share the dataset in a language that you are familiar with.
The dataset is attached as a zip file. Keeping in mind the compute, we are limiting to only
10000 sentences, of length 4-5. Randomly split these 10000 sentences into Train-Dev-Test in
70-10-20 ratio.
- Zip file consists of individual text files for Hindi and English. Also consists of a pickled
dataframe with english and hindi sentences as two columns. You can make use of either one.
