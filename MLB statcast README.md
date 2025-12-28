# 2025年 MLB Statcast Whiff%（空振り率）分析

MLBの公式データ「Statcast」をPythonで扱い、投手の「本当に打ちにくいボール」を数値化する指標、Whiff%（空振り率）を算出・可視化するプロジェクトです。

## 概要
野球データ分析の基礎である「データの集計」「フラグ立て」「ランキング可視化」の流れを網羅しています。

## 分析内容
- `pybaseball` を使用した最新データの取得
- `description` カラムから「空振り」と「スイング」を定義・フラグ化
- 最低スイング数（150回以上）のフィルタリングによる信頼性確保
- `Seaborn` を用いたランキング形式の可視化

## 使用技術
- **Language:** Python (Google Colab)
- **Libraries:** pybaseball, pandas, seaborn, matplotlib, japanize_matplotlib

## 実行方法
1. 必要なライブラリをインストールしてください。
   `pip install pybaseball japanize_matplotlib`
2. Google Colab等で本リポジトリの `.ipynb` ファイルを実行してください。

## 投稿動画
本コードの解説・写経動画をYouTubeで公開しています。
[ここにYouTubeの動画URLを貼る]
