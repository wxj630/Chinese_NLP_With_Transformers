# Chinese NLP With Transformers
transformers是[Hugging Face](https://huggingface.co)开源的自然语言处理，预训练模型库。

本仓库将基于transformers库去完成中文NLP任务，包括文本分类、序列标注、语义匹配、文本生成等任务。

完成自然语言处理5大类别任务：
1. [文本分类](https://github.com/wxj630/Chinese_NLP_With_Transformers/blob/master/text_classification.ipynb)
2. 文本匹配
   - [句子对匹配](https://github.com/wxj630/Chinese_NLP_With_Transformers/blob/master/text_match.ipynb)
   - 阅读理解：[多项选择](https://github.com/wxj630/Chinese_NLP_With_Transformers/blob/master/multi_choice.ipynb)
3. 序列标注：
  [命名实体识别](https://github.com/wxj630/Chinese_NLP_With_Transformers/blob/master/named_entity_recognition.ipynb)
   （分词Chinese Word Segmentation、词性标注Part-Of-Speech tagging实现类似）
4. 受控文本生成： 
   - [文本摘要](https://github.com/wxj630/Chinese_NLP_With_Transformers/blob/master/summarization.ipynb)
   - [机器翻译](https://github.com/wxj630/Chinese_NLP_With_Transformers/blob/master/translation_en2ro.ipynb)
   - 阅读理解：[抽取式问答](https://github.com/wxj630/Chinese_NLP_With_Transformers/blob/master/extractive_qa.ipynb) 
5. [非受控文本生成](https://github.com/wxj630/Chinese_NLP_With_Transformers/blob/master/unconditional_generation.ipynb)


transformers可以实现的模型包括以下模型：

- BERT(来自谷歌) 与论文《BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding》 一起发布；
- GPT-2(来自OpenAI) 与论文《Language Models are Unsupervised Multitask Learners》 一起发布；
- T5 (来自谷歌) 与论文《Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer》 一起发布；

BERT、GPT-2、T5刚好是目前主流的三种预训练模型架构，分别是：
- auto-encoder(自编码)：适合NLU自然语言理解任务（文本分类、文本匹配、序列标注等）；
- auto-regressive(自回归)：适合unconditional NLG非受控文本生成任务；
- encoder-decoder(编码器-解码器)：适合conditional NLG受控文本生成任务（文本摘要、机器翻译等）。

更多预训练模型的信息和新型预训练模型可以参考：
- [Pre-trained Models for Natural Language Processing: A Survey](https://arxiv.org/pdf/2003.08271.pdf) :预训练语言模型综述 from 复旦大学；
- 智源研究院[GLM模型](https://arxiv.org/abs/2103.10360) ：可同时适用于NLU、conditional NLG、unconditional NLG任务；
- 百度[ERNIE3.0](https://arxiv.org/abs/2107.02137) ：知识增强的预训练语言模型。