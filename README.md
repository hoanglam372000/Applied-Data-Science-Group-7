# Applied-Data-Science-Group-7
Group 7: \
18120429 – Phạm Trung Kiên - trungkien2000\
18120431 – A Ly Ha Kim - kim-ali\
18120434 – Thái Hoàng Lâm - hoanglam372000\
18120462 – Nguyễn Thị Mận - ManCB26

Link GG collab (code + report): https://colab.research.google.com/drive/1MpqKtl-ZOP-IyxNhJKwlxmaSAs4kPFyT#scrollTo=iw8LntxSaG5H&uniqifier=5 \
Kết quả cuối cùng đạt được: \
- Private score: 0.64833

Link GG Sheet meeting: https://docs.google.com/spreadsheets/d/1saYIZIALNaFdzqsYtm-3_ynxzbSlgfn5YKSnog32DxA/edit?usp=sharing


Bài toán: Tweet Sentiment Extraction
Phương pháp giải quyết:
  Ban đầu nhóm định theo hướng giải quyết của người đứng hạng 3 trên private leaderboard, đó là sử dụng RoBerta. Phương hướng tiếp cận của nhóm đã vẽ ra như sau:
+ Nhóm tiến hành giải bài toán theo cách riêng của nhóm: Học thống kê
+ Sau khi ra kết quả training, nếu chưa đạt được kết quả nằm trong top 20 của private leaderboard, thì nhóm sẽ tiếp tục tiếp cận dần các phương pháp Deep learning
+ Sau cùng, nếu vẫn chưa đạt được kết quả khả quan với những kiến thức deep learning đã học, nhóm sẽ tiến hành giải tiếp bài toán theo phương pháp của hạng 3 (lúc này các thành viên đã đủ kiến thức)

Data: Train.csv, test.csv, sample_submission.csv are downloaded from Kaggle (https://www.kaggle.com/c/tweet-sentiment-extraction/data) \
The data is used to carry on the project from Applied Data Science course of VNU HCMUS, for the purpose of scientific research.

 Một số paper về Deep learning nhóm đã tham khảo:
- LSTM: https://arxiv.org/pdf/1503.04069.pdf
- Attention +  Transformer: https://arxiv.org/pdf/1706.03762.pdf
- BERT: https://arxiv.org/pdf/1810.04805.pdf
- Cách sử dụng: thông qua thư viện Tensorflow, Transformer: https://huggingface.co/docs/transformers/quicktour
