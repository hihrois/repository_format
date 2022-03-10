# source
put code sources.
pythonスクリプトを置く。処理の時系列（データ取得=>前処理=>モデル学習=>可視化）でフォルダを分けたほうが親切。

## /data
分析に使うcsvをpandasのdata frame入れる所まで。

## /features
data frameをモデルに学習させる形式に変換するところまで。前処理。

## /models
前処理したデータを学習させるところまで。

## /figures
MTGでの報告・論文作成用の図を作成するスクリプトを置く。無くても良いかも。