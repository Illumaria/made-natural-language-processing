# Natural Language Processing (MADE S02E02)
This repository contains materials for the Natural Language Processing course.

**Tip #1:**

Loading the entire repository can take a considerable amount of time. A single folder can be downloaded via [DownGit](https://downgit.github.io/).

**Tip #2:**

Sometimes GitHub failes to render a notebook. In that case use [nbviewer](https://nbviewer.jupyter.org/) — it works like a charm!

**Tip #3:**

In those cases when *nbviewer* fails to find a notebook whereas GitHub finds it just fine, try to add `?flush_cache=false` at the end of the *nbviewer* link.

Legend: ![](https://github.com/Illumaria/made-deep-learning/blob/master/icons/pdf.png) — slides, ![](https://github.com/Illumaria/made-deep-learning/blob/master/icons/jupyter.png) — code, ![](https://github.com/Illumaria/made-deep-learning/blob/master/icons/youtube.png) — video.

Week | What | Where | When
:--: | :--: | :---: | :--:
[1](https://data.mail.ru/curriculum/program/lesson/16177/) | Tasks in NLP, text preprocessing (tokenization, normalization (stemming, lemmatization)), feature extraction (Bag-of-Words, Bag-of-Ngramms, TF-IDF), word embeddings (one-hot, matrix factorization, word2vec, CBOW, Skip-gram, GloVe). | [![](https://github.com/Illumaria/made-deep-learning/blob/master/icons/pdf.png)](https://github.com/Illumaria/made-natural-language-processing/blob/master/01-word-embeddings/01_word_embeddings.pdf) [![](https://github.com/Illumaria/made-deep-learning/blob/master/icons/jupyter.png)](https://nbviewer.jupyter.org/github/Illumaria/made-natural-language-processing/blob/master/01-word-embeddings/01_word_embeddings.ipynb) [![](https://github.com/Illumaria/made-deep-learning/blob/master/icons/youtube.png)](https://youtu.be/UARNjbAF5x4) | 10.03.2021
[2](https://data.mail.ru/curriculum/program/lesson/16178/) | Embeddings: recap (word2vec), usage in unsupervised translation; cosine distance; RNNs, CNNs, n-grams, and their usage examples. | [![](https://github.com/Illumaria/made-deep-learning/blob/master/icons/pdf.png)](https://github.com/Illumaria/made-natural-language-processing/blob/master/02-cnn-for-texts-and-more-embeddings/02_cnn_for_texts_and_more_embeddings.pdf) [![](https://github.com/Illumaria/made-deep-learning/blob/master/icons/jupyter.png)](https://nbviewer.jupyter.org/github/Illumaria/made-natural-language-processing/blob/master/02-cnn-for-texts-and-more-embeddings/02_cnn_for_texts.ipynb) [![](https://github.com/Illumaria/made-deep-learning/blob/master/icons/youtube.png)](https://youtu.be/4MkfeS3Sn2Y) | 17.03.2021
[3](https://data.mail.ru/curriculum/program/lesson/16179/) | Recap: RNN; LSTM, gates in LSTM; RNNs as encoders for sequential data; vanishing gradient problem; exploding gradient problem. | [![](https://github.com/Illumaria/made-deep-learning/blob/master/icons/pdf.png)](https://github.com/Illumaria/made-natural-language-processing/blob/master/03-lstm-gru-vanishing-gradient/03_lstm_gru_vanishing_gradient.pdf) [![](https://github.com/Illumaria/made-deep-learning/blob/master/icons/jupyter.png)](https://nbviewer.jupyter.org/github/Illumaria/made-natural-language-processing/blob/master/03-lstm-gru-vanishing-gradient/03_bilstm_for_pos_tagging.ipynb) [![](https://github.com/Illumaria/made-deep-learning/blob/master/icons/youtube.png)](https://youtu.be/fBROi7v6QNM) | 24.03.2021
[4](https://data.mail.ru/curriculum/program/lesson/16180/) | Neural Machine Translation (NMT): problem statement, historical overview, statistical MT, beam search, BLEU/perplexity scores; Encoder-Decoder architecture, attention. | [![](https://github.com/Illumaria/made-deep-learning/blob/master/icons/pdf.png)](https://github.com/Illumaria/made-natural-language-processing/blob/master/04-machine-translation-and-attention/04_machine_translation_and_attention.pdf) [![](https://github.com/Illumaria/made-deep-learning/blob/master/icons/jupyter.png)](https://nbviewer.jupyter.org/github/Illumaria/made-natural-language-processing/blob/master/04-machine-translation-and-attention/04_attention_basics.ipynb) [![](https://github.com/Illumaria/made-deep-learning/blob/master/icons/youtube.png)](https://youtu.be/2ExTrSrCoKs) | 31.03.2021
[5](https://data.mail.ru/curriculum/program/lesson/16181/) | Recap: attention in seq2seq; Transformer architecture, self-attention. | [![](https://github.com/Illumaria/made-deep-learning/blob/master/icons/pdf.png)](https://github.com/Illumaria/made-natural-language-processing/blob/master/05-self-attention-and-transformer/05_self_attention_and_transformer.pdf) [![](https://github.com/Illumaria/made-deep-learning/blob/master/icons/jupyter.png)](https://nbviewer.jupyter.org/github/Illumaria/made-natural-language-processing/blob/master/05-self-attention-and-transformer/05_tensorboard_and_char_level_machine_translation.ipynb) [![](https://github.com/Illumaria/made-deep-learning/blob/master/icons/youtube.png)](https://youtu.be/938KmoCXh84) | 07.04.2021
[6](https://data.mail.ru/curriculum/program/lesson/16182/) | Recap: self-attention; positional encoding, layer normalization, decoder in Transformer. | [![](https://github.com/Illumaria/made-deep-learning/blob/master/icons/pdf.png)](https://github.com/Illumaria/made-natural-language-processing/blob/master/06-transformer-and-positional-encoding/06_transformer_and_positional_encoding.pdf) [![](https://github.com/Illumaria/made-deep-learning/blob/master/icons/jupyter.png)](https://nbviewer.jupyter.org/github/Illumaria/made-natural-language-processing/blob/master/06-transformer-and-positional-encoding/06_positional_encoding.ipynb) [![](https://github.com/Illumaria/made-deep-learning/blob/master/icons/jupyter.png)](https://nbviewer.jupyter.org/github/Illumaria/made-natural-language-processing/blob/master/06-transformer-and-positional-encoding/06_seq2seq_nmt_and_tensorboard.ipynb) [![](https://github.com/Illumaria/made-deep-learning/blob/master/icons/youtube.png)](https://youtu.be/6iPcuIcF7Qg) | 14.04.2021
[7](https://data.mail.ru/curriculum/program/lesson/16183/) | OpenAI Transformer (pre-training decoder for language modeling), ELMo (deep contextualized word representations), BERT. | [![](https://github.com/Illumaria/made-deep-learning/blob/master/icons/pdf.png)](https://github.com/Illumaria/made-natural-language-processing/blob/master/07-context-based-embeddings-and-bert/07_bert.pdf) [![](https://github.com/Illumaria/made-deep-learning/blob/master/icons/jupyter.png)](https://nbviewer.jupyter.org/github/Illumaria/made-natural-language-processing/blob/master/07-context-based-embeddings-and-bert/07_bert_for_text_classification.ipynb) [![](https://github.com/Illumaria/made-deep-learning/blob/master/icons/youtube.png)](https://youtu.be/A22G9i1Vbkk) | 21.04.2021
[8](https://data.mail.ru/curriculum/program/lesson/16184/) | ULMFiT, Transformer-XL, Question Answering (SQuAD, SberQuAD, ODQA), GPT. | [![](https://github.com/Illumaria/made-deep-learning/blob/master/icons/pdf.png)](https://github.com/Illumaria/made-natural-language-processing/blob/master/08-question-answering/08_question_answering.pdf) [![](https://github.com/Illumaria/made-deep-learning/blob/master/icons/jupyter.png)](https://nbviewer.jupyter.org/github/Illumaria/made-natural-language-processing/blob/master/08-question-answering/08_qa_with_bert_and_tts.ipynb) [![](https://github.com/Illumaria/made-deep-learning/blob/master/icons/youtube.png)](https://youtu.be/OgJKakEx2oM) | 28.04.2021

Additional materials:
* **word embeddings**:
  * [Word Embeddings](https://lena-voita.github.io/nlp_course/word_embeddings.html) (by Lena Voita)
  * [Word2vec tutorial](http://mccormickml.com/2016/04/19/word2vec-tutorial-the-skip-gram-model/)
  * [Illustrated word2vec](http://jalammar.github.io/illustrated-word2vec/) (by Jay Alammar)
* **CNNs**:
  * [CS231n page about CNNs](https://cs231n.github.io/convolutional-networks/)
  * [Report on Text Classification using CNN, RNN and HAN](https://medium.com/jatana/report-on-text-classification-using-cnn-rnn-han-f0e887214d5f)
  * [CNNs for Sentence Classification](https://arxiv.org/abs/1408.5882)
* **LSTM and PoS tagging**:
  * [PoS tagging](https://medium.com/analytics-vidhya/part-of-speech-tagging-what-when-why-and-how-9d250e634df6)
  * [Text classification with RNNs and CNNs](https://medium.com/jatana/report-on-text-classification-using-cnn-rnn-han-f0e887214d5f)
* **Transformers**:
  * [Illustrated Transformer](https://jalammar.github.io/illustrated-transformer/) (by Jay Alammar)
  * [The Annotated Transformer](https://nlp.seas.harvard.edu/2018/04/03/attention.html) (by Harvard NLP group)
* **BERT**:
  * [The Illustrated BERT, ELMo, and co. (How NLP Cracked Transfer Learning)](http://jalammar.github.io/illustrated-bert/) (by Jay Alammar)
  * [Simple tutorial for distilling BERT](https://towardsdatascience.com/simple-tutorial-for-distilling-bert-99883894e90a) (by Paul Gladkov)
  * [Huggingface Transformers](https://github.com/huggingface/transformers)
* **Question Answering and TTS**:
  * [SberQuAD — Russian Reading Comprehension Dataset: Description and Analysis](https://arxiv.org/pdf/1912.09723.pdf)
  * [GPT-3 for Russian language](https://habr.com/ru/company/sberbank/blog/524522/)
  * [Voice cloning](https://habr.com/ru/post/465941/)
  * [Tacotron 2 Demo](https://pytorch.org/hub/nvidia_deeplearningexamples_tacotron2/) (by NVIDIA)
  * [Voice datasets](https://voice.mozilla.org/ru/datasets) (by Mozilla)
  * [Speech recognition and synthesis (ASR and TTS)](https://docs.deeppavlov.ai/en/0.9.1/features/models/nemo.html) (by DeepPavlov)
  * [Russian Open Speech To Text (STT/ASR) Dataset](https://github.com/snakers4/open_stt)
  * [DeepSpeech 0.6: Mozilla’s Speech-to-Text Engine Gets Fast, Lean, and Ubiquitous](https://hacks.mozilla.org/2019/12/deepspeech-0-6-mozillas-speech-to-text-engine/) (by Reuben Morais)
  * [Open Domain Question Answering Skill on Wikipedia](http://docs.deeppavlov.ai/en/master/features/skills/odqa.html) (by DeepPavlov)
