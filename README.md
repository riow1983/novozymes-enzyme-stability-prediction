# novozymes-enzyme-stability-prediction

![header](https://github.com/riow1983/novozymes-enzyme-stability-prediction/blob/main/png/header.png)<br>
https://www.kaggle.com/competitions/novozymes-enzyme-stability-prediction<br>
どんなコンペ?:<br>
```
[コンペ名称]

[URL]
https://www.kaggle.com/competitions/novozymes-enzyme-stability-prediction

[コンペ概要]

[コンペ開催期間]

[希望参加期間 (コンペ終了後の振り返り期間含む)]

[参加希望者]

[どのような経験が得られるか]

[ビジネスにどう活かせるか]
```
<br>

開催期間:<br>
![timeline](https://github.com/riow1983/novozymes-enzyme-stability-prediction/blob/main/png/timeline.png)<br>
[結果](#2023-01-03)<br>  
<br>
<br>
<br>
***

## 実験管理テーブル
https://wandb.ai/riow1983/novozymes-enzyme-stability-prediction?workspace=user-riow1983
|commitSHA|comment|W&B|Local CV|Public LB|Private LB|
|----|----|----|----|----|----|
<br>

## Late Submissions
|commitSHA|comment|W&B|Local CV|Public LB|Private LB|
|----|----|----|----|----|----|
<br>


## My Assets
[notebook命名規則]  
- kagglenb001{e,t,i}-hoge.ipynb: Kaggle platform上で新規作成されたKaggle notebook (kernel).
- nb001{e,t,i}-hoge.ipynb: localで新規作成されたnotebook. 
- {e:EDA, t:train, i:inference}
- kaggle platform上で新規作成され, localで編集を加えるnotebookはファイル名kagglenbをnbに変更し, 番号は変更しない.

#### Code
作成したnotebook等の説明  
|name|url|status|comment|
|----|----|----|----|
<br>





***
## 参考資料
#### Snipets
```python
proj_name = 'HOGE'
nb_name = 'hogehoge'

import sys
import os
from pathlib import Path

KAGGLE_ENV = True if 'KAGGLE_URL_BASE' in set(os.environ.keys()) else False

if KAGGLE_ENV:
    INPUT_DIR = Path('../input')
    OUTPUT_DIR = Path('')
else:
    if "google.colab" in sys.modules:
        from google.colab import drive
        drive.mount("/content/drive")
        base = f"/content/drive/MyDrive/colab_notebooks/kaggle/{proj_name}"
    else:
        base = '..'
    INPUT_DIR = Path(f"{base}/input/")
    
    os.mkdirs(INPUT_DIR.as_posix(), exist_ok=True)
    OUTPUT_DIR = INPUT_DIR / nb_name
    os.mkdirs(OUTPUT_DIR.as_posix(), exist_ok=True)
```
<br>


#### Papers
|name|url|status|comment|
|----|----|----|----|
<br>


#### Blogs (Medium / Qiita / Others)
|name|url|status|comment|
|----|----|----|----|
|第2回 地球から細胞が生まれた1|[URL](https://www.yodosha.co.jp/jikkenigaku/mb_lecture_ex/vol2n1.html)|Done|the birth of biomolecules|
<br>


#### Documentation (incl. Tutorial)
|name|url|status|comment|
|----|----|----|----|
|MIA: Multimodal single-cell data, open benchmarks, and a NeurIPS 2021 competition|[URL](https://youtu.be/ZXDILOyiy7A)|Watching|コンペホストによるYouTube動画.<br>議論中心.|
<br>

#### BBC (StackOverflow / StackExchange / Quora / Reddit / Others)
|name|url|status|comment|
|----|----|----|----|
<br>

#### GitHub
|name|url|status|comment|
|----|----|----|----|
<br>

#### Hugging Face
|name|url|status|comment|
|----|----|----|----|
<br>

#### Colab Notebook
|name|url|status|comment|
|----|----|----|----|
<br>

#### Kaggle (Notebooks)
|name|url|status|comment|
|----|----|----|----|
<br>

#### Kaggle (Datasets)
|name|url|status|comment|
|----|----|----|----|
<br>

#### Kaggle (Discussion)
|name|url|status|comment|
|----|----|----|----|
<br>



***
## Diary

#### 2022-12-23
<br>
<br>
<br>

#### 2023-01-03
結果はxxx/xxx (暫定) だった. <br>
![private lb image](https://github.com/riow1983/novozymes-enzyme-stability-prediction/blob/main/png/result.png)
<br>
<br>
**どのように取り組み, 何を反省しているか**<br>
**My submissions について**<br>
**xxxについて**<br>
<br>
<br>
<br>
Back to [Top](#novozymes-enzyme-stability-prediction)



