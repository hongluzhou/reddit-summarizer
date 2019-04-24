# reddit-summarizer
Rutgers 2019 spring NLP course project
  
## Final Presentation: google sides [link](https://docs.google.com/presentation/d/1G_7menqhi7S85ShZDGjWppuFmY8TWyW9-CWyI5zE1ts/edit)   
    
### TODO notes
- 2019-04-17   
  - [x] Check Darpa dataset, downlownd and put them in one place. Identify which ones to use and evaluate the possibility of using and potential issues.
      - Darpa dataset and its schema have been uploaded in google folder. Use the Cyber one first. "selftext_m" key is for text, and "title_m" key is for title.    
  - [x] Check other public Reddit dataset. 
  - [ ] Read tutorials.    
  - [ ] Read papers and tutorials regarding summarization task evaluation metrics.
    
### Resources
- [google folder](https://drive.google.com/drive/folders/1X9Z8pT9eW3bUdGQT7OO14Oqd5a2_kjgU?usp=sharing)  
- [first presentation: Can we summarize Reddit post?](https://drive.google.com/open?id=17K7eExQMPfkpm5kd36QmMrdwFPA1GfAS)   
- [online reddit summarizer bot](https://www.reddit.com/r/autotldr/comments/31b9fm/faq_autotldr_bot/)   
- [text compactor tool](https://www.textcompactor.com/)    
- [TL;DR The abstractive summarization challenge](https://www.reddit.com/r/MachineLearning/comments/a6erpw/project_the_tldr_challenge/). Good dataset to use! An on-going challenge.   
- [What is the state of text summarization research?](https://www.reddit.com/r/LanguageTechnology/comments/94m0kw/what_is_the_state_of_text_summarization_research/).  
- [Datasets for text document summarization?](https://www.reddit.com/r/MachineLearning/comments/48wqey/datasets_for_text_document_summarization/)   
- [A Quick Introduction to Text Summarization in Machine Learning](https://towardsdatascience.com/a-quick-introduction-to-text-summarization-in-machine-learning-3d27ccf18a9f). Described the types of techniques.    

### Tutorials & Tools
- [Encoder-Decoder Models for Text Summarization in Keras](https://machinelearningmastery.com/encoder-decoder-models-text-summarization-keras/), [code](https://github.com/chen0040/keras-text-summarization).    
- [Text Summarization Using Keras Models](https://hackernoon.com/text-summarization-using-keras-models-366b002408d9)     
- [tensor2tensor](https://github.com/tensorflow/tensor2tensor)    
- [fairseq](https://github.com/pytorch/fairseq)    
- [A ten-minute introduction to sequence-to-sequence learning in Keras](https://blog.keras.io/a-ten-minute-introduction-to-sequence-to-sequence-learning-in-keras.html)   
- [Keras exmaple code: English to French](https://github.com/keras-team/keras/blob/master/examples/lstm_seq2seq.py)    
        
### Metrics   
- [ROUGE](https://en.wikipedia.org/wiki/ROUGE_(metric))   
   
### Papers   
- [Abstractive Summarization of Reddit Posts with Multi-level Memory Networks](https://github.com/ctr4si/MMN). Dataset provided but no implementation.      
- [Get To The Point: Summarization with Pointer-Generator Networks](https://arxiv.org/pdf/1704.04368.pdf)  
- [Generating News Headlines with Recurrent Neural Networks](https://arxiv.org/abs/1512.01712)    
- [Sequence to Sequence Learning with Neural Networks](https://papers.nips.cc/paper/5346-sequence-to-sequence-learning-with-neural-networks.pdf). Proposed Seq2Seq.

### More thinking and future work notes
- Attention mechanism should help.   
- Comparison between character-level model and word-level model.    
- Could we use hidden vector of the model to serve as embedding vector of the text, and further do other tasks like subreddit classification etc?   
