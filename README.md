# PRED (Psychology Relation Extraction Dataset)

## Introduction
- Naver Boostcamp AI Tech
- NLP Data Annotation Project

### 🔅 Members

김대웅|김채은|김태욱|유영재|이하람|진명훈|허진규|
:-:|:-:|:-:|:-:|:-:|:-:|:-:
<img src='https://avatars.githubusercontent.com/u/41335296?v=4' height=80 width=80px></img>|<img src='https://avatars.githubusercontent.com/u/60843683?v=4' height=80 width=80px></img>|<img src='https://avatars.githubusercontent.com/u/47404628?v=4' height=80 width=80px></img>|<img src='https://avatars.githubusercontent.com/u/53523319?v=4' height=80 width=80px></img>|<img src='https://avatars.githubusercontent.com/u/35680202?v=4' height=80 width=80px></img>|<img src='https://avatars.githubusercontent.com/u/37775784?v=4' height=80 width=80px></img>|<img src='https://avatars.githubusercontent.com/u/88299729?v=4' height=80 width=80px></img>
[Github](https://github.com/KimDaeUng)|[Github](https://github.com/Amber-Chaeeunk)|[Github](https://github.com/taeukkkim)|[Github](https://github.com/uyeongjae)|[Github](https://github.com/hrxorxm)|[Github](https://github.com/jinmang2)|[Github](https://github.com/JeangyuHeo)

## Data Information
- Train: 724
- Dev: 182
- \# of class: 11
    ```
    '관계_없음' '이론:대체어' '이론:상위_이론' '이론:하위_이론'
    '이론:상위_학문분야' '학문분야:하위_이론' '인물:소속이론또는학문분야'
    '용어:치료기법' '용어:약' '용어:증상또는질환' '용어:대체어'
    ```

## Methodology

### Guideline & Relation map

- [google docs](https://docs.google.com/document/d/1Qf8lenJtMQ_XOTBEEM6Kiz-d1_3ZOCg1/edit?usp=sharing&ouid=106498369085903094431&rtpof=true&sd=true
)

### Evaluation
- Fleiss' Kappa

![Untitled](https://user-images.githubusercontent.com/37775784/142575313-066123c8-dd67-401d-a15b-197f3f1e4f3c.png)

## Baseline code
```
.
├── assets/wrapup_level3_nlp_annot_14.pdf
├── dataset
│   ├── dev.csv
│   └── train.csv
├── code
│   ├── constant.py
│   ├── evaluation.py
│   ├── inference.py
│   ├── load_data.py
│   └── utils
│         ├── calculate_iaa.py
│         └── fleiss.py
├── .gitignore
└── README.md
```

### train

```shell
python code/train.py
```
