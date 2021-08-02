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
4. 受控文本生成： 
   - [文本摘要](https://github.com/wxj630/Chinese_NLP_With_Transformers/blob/master/summarization.ipynb)
   - [机器翻译](https://github.com/wxj630/Chinese_NLP_With_Transformers/blob/master/translation_zh2en.ipynb)
   - 阅读理解：[抽取式问答](https://github.com/wxj630/Chinese_NLP_With_Transformers/blob/master/extractive_qa.ipynb) 
5. [非受控文本生成](https://github.com/wxj630/Chinese_NLP_With_Transformers/blob/master/unconditional_generation.ipynb)


transformers可以实现的模型包括以下模型等：

- BERT(来自谷歌) 与论文《BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding》 一起发布
- GPT-2(来自OpenAI) 与论文 《Language Models are Unsupervised Multitask Learners》 一起发布
- XLNet (来自谷歌/CMU) 与论文   《XLNet: Generalized Autoregressive Pretraining for Language Understanding》 一起发布
