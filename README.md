# Sentence-anomaly-detection

Detect anomalous sentences using Universal Sentence Encoder and the technique of anomaly detection in directional data. <br>
See https://qiita.com/jovyan/items/e5d2dc7ffabc2353db38 for deteails (in Japanese).

--- 
Universal Sentence Encoderと方向データに対する異常検知を組み合わせて、文章の中に混じった異質な文章を検出するモデルを作成する。<br>
詳細は https://qiita.com/jovyan/items/e5d2dc7ffabc2353db38 を参照のこと。

## Usage
```
docker build -t anodetection .
docker run -it --name anodetection-1 -p 8889:8889 anodetection
```
Open the notebook main_notebook.ipynb in jupyter lab.

