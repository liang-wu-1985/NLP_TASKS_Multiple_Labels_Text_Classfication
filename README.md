# NLP_TASKS_Multiple_Labels_Text_Classfication
Help customers division to figure out which categories  comment belongs to

It is important to explain the difference between a multi-class classification problem and a multi-label classification. In multi-class classification problem, an instance or a record can belong to one and only one of the multiple output classes. For instance, in the sentiment analysis problem that we studied in the last article, a text review could be either "good", "bad", or "average". It could not be both "good" and "average" at the same time. On the other hand in multi-label classification problems, an instance can have multiple outputs at the same time. For instance, in the text classification problem that we are going to solve in this article, a comment can have multiple tags. These tags include "toxic", "obscene", "insulting", etc., at the same time.

For metric we'r going to use is binary_crossentropy instead of categorical_crossentropy.

In this example, BiGRU+BiLSTM gave me a good performance than others. (used GPU to boost training)

<B>Text Classification Using Hierarchical Attention Network (HAN) :</B>

I have taken reference from this research paper <B>Hierarchical Attention Networks for Document Classification</B>. It can be a great guide for Document Classification using HAN.  The pre-trained embedding we’ll be using is Fasttext.
