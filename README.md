# ML-Iris-classification（機械学習を用いたアヤメの分類）
アヤメのがく片と花びらの長さと幅のデータを用いて、アヤメの花の種類を分類するモデルを作成します。

## モデルの解説記事
[[機械学習]初心者に向けてアヤメ分類を一から解説してみた(Qiita)](https://qiita.com/Hirochon/items/12379d7ca6141f1fb6fa)

## 開発環境
- Python 3.7.3
- Numpy 1.16.4
- Pandas
- Matplotlib 3.1.0
- scikit-learn 0.21.3

## プログラムの流れ
1. 鉄板ライブラリをimport
2. scikit-learn内の機能をimport
3. アヤメのデータセットに何が入っているか見ていく
4. Pandasを使ってデータを分かりやすくまとめる
5. train_test_splitでデータセットを分割
6. Matplotlibでデータを可視化
7. 機械学習アルゴリズムの実装
