# Toxic Detection In Web 

Krátko: súbor zošitov Jupyter s príkladmi na trénovanie modelov (LSTM, DistilBERT) na klasifikáciu toxických data v angličtine a slovenčine.

- `slovaktensorflow.ipynb`.  
Učenie LSTM na slovenskom datasete.  
- `endLSTM.ipynb`.  
Učenie LSTM na súbore údajov v slovenčine.
- `slovakDistilbert.ipynb`.  
Transformátorové učenie DistilBERT na slovenskom datasete.  
- `engDistilBert.ipynb`.  
Transformátorové učenie DistilBERT na anglickom datasete.

## Sťahovanie dát

1. Jigsaw Toxic Comment (angličtina)**  
   - Zaregistrujte sa na [Kaggle](https://www.kaggle.com/) (ak ešte nemáte konto).  
   - Prejdite na súťaž **Jigsaw Toxic Comment Classification Challenge**:  
     https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data  
   - Stiahnite si súbory `train.csv` a `test.csv`
     jigsaw-toxic-comment-classification-challenge/
  
2. Slovenské toxické komentáre (slovenčina)
   - Navštívte GitHub repozitár so slovenskými komentármi
     https://github.com/yourusername/slovak-toxic-comments](https://huggingface.co/datasets/TUKE-KEMT/hate_speech_slovak)
   - Stiahnite súbory `slovak_train.csv` a `slovak_test.csv` a uložte ich do priečinka  
     slovakdata/
3. Slovenské vektory (FastText)
   - Stiahnite predtrénované vektory zo stránky FastText:  
     https://dl.fbaipublicfiles.com/fasttext/vectors-crawl/cc.sk.300.vec.gz
   - Rozbaľte archív v koreňovom adresári projektu:  
     gzip -d cc.sk.300.vec.gz


## Dokumentácia

- [Príloha B – Systémová príručka](Priloha_B.pdf)  
- [Príloha C – Zadávací list](Priloha_C.pdf)
