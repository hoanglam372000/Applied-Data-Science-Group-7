# Applied-Data-Science-Group-7
Group 7: \
18120434 – Thái Hoàng Lâm - hoanglam372000 (LEADER) \
18120429 – Phạm Trung Kiên - trungkien2000\
18120431 – A Ly Ha Kim - kim-ali\
18120462 – Nguyễn Thị Mận - ManCB26

Link GG collab (code + report): https://colab.research.google.com/drive/1MpqKtl-ZOP-IyxNhJKwlxmaSAs4kPFyT#scrollTo=iw8LntxSaG5H&uniqifier=5 \
Final score (scored by Kaggle) in Private Leaderboard: 0.64833

Link GG Sheet meeting: https://docs.google.com/spreadsheets/d/1saYIZIALNaFdzqsYtm-3_ynxzbSlgfn5YKSnog32DxA/edit?usp=sharing


Problem: Tweet Sentiment Extraction \
Solution: 
  - Baseline: Extract with statistical approach (Bayes Probability)
  - Advance: Deep learning approach
    + Word embeddings with CBOW and LSTM with Attention mechanism model.
    + BERT, RoBerta for word representation
  - Hydrid: combining statistical model and Roberta model \

Data sets: Train.csv, test.csv, sample_submission.csv are downloaded from Kaggle (https://www.kaggle.com/c/tweet-sentiment-extraction/data) \
The data is used to carry on the project from Applied Data Science course of VNU HCMUS, for the purpose of scientific research. \

 References:
- LSTM: https://arxiv.org/pdf/1503.04069.pdf
- Attention +  Transformer: https://arxiv.org/pdf/1706.03762.pdf
- BERT: https://arxiv.org/pdf/1810.04805.pdf
- Tensorflow, Transformer: https://huggingface.co/docs/transformers/quicktour
