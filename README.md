# BFcorticalparc-smk_PNI

## 概要
本リポジトリは、dMRI及びrefMRIデータを用いた脳領域分割パイプラインを、PNI 7テスラデータに適用・最適化したものです。

## 使用技術・ツール
- Snakemake
- FSL（probtrackx2）
- FreeSurfer
- ANTs
- Connectome Workbench
- Singularity

## ディレクトリ構成
- config/ : 設定ファイル
- workflow/ : Snakemakeルール
- scripts/ : 処理スクリプト
- resources/ : マスク

## 実行方法

### 1. 環境構築
必要なツールをインストールする

### 2. 実行
```bash
snakemake -j 1
