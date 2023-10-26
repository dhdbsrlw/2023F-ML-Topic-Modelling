# 2023F-ML-Topic-Modelling
2023F-Machine Learning Term Project: Topic Modelling on Amazon Review Data
### Pipeline: \ 
1. Data loader (Preprocessed)
2. Document embedding
3. Sentence Transformer
4. Dimension Reduction (UMAP)
5. Clustering (HDBScan)
6. Topic extraction (LDA, C-TF-IDF from BERTopic)

## Directory Structure
./ \
├─ Final.ipynb ────────────────── All codes for this report \
├─ result ─────────────────────── Directory to store experiment  \
└─ dataset \
   ├─ beauty.csv ──────────────── Main dataset with 30,000 beauty reviews \
   └─ whole.csv ───────────────── 100,000 reviews of movie, beauty, hotel
   
## 코드 실행 시 주의사항
Final.ipynb 실행 시, workspace path 를 환경에 맞게 (path 를) 재설정해주어야 한다. \
예) /content/drive/MyDrive/Final_submit 

. \
. \
. \
Last Update: 2023/10/26 (기계학습 종강 !)
