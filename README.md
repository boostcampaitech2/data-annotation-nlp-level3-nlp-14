# PRED (Psychology Relation Extraction Dataset)

## Introduction
- Naver Boostcamp AI Tech
- NLP Data Annotation Project

### π Members

κΉλμ|κΉμ±μ|κΉνμ±|μ μμ¬|μ΄νλ|μ§λͺν|νμ§κ·|
:-:|:-:|:-:|:-:|:-:|:-:|:-:
<img src='https://avatars.githubusercontent.com/u/41335296?v=4' height=80 width=80px></img>|<img src='https://avatars.githubusercontent.com/u/60843683?v=4' height=80 width=80px></img>|<img src='https://avatars.githubusercontent.com/u/47404628?v=4' height=80 width=80px></img>|<img src='https://avatars.githubusercontent.com/u/53523319?v=4' height=80 width=80px></img>|<img src='https://avatars.githubusercontent.com/u/35680202?v=4' height=80 width=80px></img>|<img src='https://avatars.githubusercontent.com/u/37775784?v=4' height=80 width=80px></img>|<img src='https://avatars.githubusercontent.com/u/88299729?v=4' height=80 width=80px></img>
[Github](https://github.com/KimDaeUng)|[Github](https://github.com/Amber-Chaeeunk)|[Github](https://github.com/taeukkkim)|[Github](https://github.com/uyeongjae)|[Github](https://github.com/hrxorxm)|[Github](https://github.com/jinmang2)|[Github](https://github.com/JeangyuHeo)

## Data Information
- Train: 724
- Dev: 182
- \# of class: 11
    ```
    'κ΄κ³_μμ' 'μ΄λ‘ :λμ²΄μ΄' 'μ΄λ‘ :μμ_μ΄λ‘ ' 'μ΄λ‘ :νμ_μ΄λ‘ '
    'μ΄λ‘ :μμ_νλ¬ΈλΆμΌ' 'νλ¬ΈλΆμΌ:νμ_μ΄λ‘ ' 'μΈλ¬Ό:μμμ΄λ‘ λλνλ¬ΈλΆμΌ'
    'μ©μ΄:μΉλ£κΈ°λ²' 'μ©μ΄:μ½' 'μ©μ΄:μ¦μλλμ§ν' 'μ©μ΄:λμ²΄μ΄'
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
βββ assets/wrapup_level3_nlp_annot_14.pdf
βββ dataset
β   βββ dev.csv
β   βββ train.csv
βββ code
β   βββ constant.py
β   βββ evaluation.py
β   βββ inference.py
β   βββ load_data.py
β   βββ utils
β         βββ calculate_iaa.py
β         βββ fleiss.py
βββ README.md
```

### train

```shell
python code/train.py
```
