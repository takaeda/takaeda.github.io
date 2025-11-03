---
title: Yoshio Takaeda | Portfolio
description: データエンジニア・研究者 / 高次元時系列解析・製造業向け技術開発
lang: ja
---

# 高枝 佳男（Yoshio Takaeda）
**Data Engineer / Researcher / Lecturer**  
製造現場のデータを扱い、予兆検知・安定制御の研究開発を行っています。

> 混沌の整理はAIに任せ、人間は勇気をもって次元を追加する。

- [English Version](/en/)

---

## 概要

製造業のプロセス設計・データエンジニアリング・解析基盤構築に30年従事。化学プラントの設計から始まり、ゲノム解析エンジン、高分子材料データベース、そして現在の高次元時系列データ解析まで、一貫してデータ駆動型の問題解決に取り組んでいます。

現在は上智大学大学院で「高次元データ実用解析」を担当し、理論と実装の橋渡しを実践しています。

---

## 経歴

### 学歴
**京都大学大学院 工学研究科** / 博士（工学）  
高分子化学専攻、高分子分子論講座（1995年修了）

### 職歴

**上智大学大学院 応用データサイエンス学位プログラム** / 非常勤講師  
2023年9月 - 現在
- 「高次元データ実用解析」担当
- 理論から実装まで一貫した教育、実務課題を題材とした演習

**toor Inc.** / 創業者・研究開発責任者  
2012年1月 - 現在
- 高次元時系列データ解析技術（toorPIA）の研究開発
- 製造業向けデータ基盤・予兆検知システムの実証研究
- オープンソースプロジェクトの推進

**上場ベンチャー企業** / 技術責任者  
2006年8月 - 2012年1月
- 知財管理システムの技術開発・データ基盤の設計構築
- CTO/COOとして技術戦略とオペレーション最適化を主導

**三菱総合研究所** / 主任研究員  
1998年7月 - 2006年7月
- **国際ヒトゲノムプロジェクト**：ゲノム相同性検索エンジンの開発
- **高分子材料データベース**：設計・開発・実装
- 産業向けデータ解析・シミュレーション技術の研究開発

**東燃化学株式会社** / 研究開発エンジニア  
1995年4月 - 1998年6月
- PP/PEポリマー製造プラントの設計と実装
- プロセスデータエンジニアリング＆解析
- 化学プロセスの最適化と品質管理

---

## 技術的専門性

### コアスキル

**30年超にわたるデータエンジニアリング**  
化学プラント設計からゲノム解析、高分子材料DB、製造装置の予兆検知まで、データ駆動型の問題解決を一貫して追求

**高次元時系列解析**  
数百から数千におよぶ製造装置のプロセス管理パラメータを多次元ベクトルとして扱い、複雑系の状態遷移を最適な時間スケールでシームレス(連続的)に可視化することにより、系の動的特性や近未来予測(予兆検知)を実現。

**音響信号による予兆検知**  
DSP処理とRaspberry Pi + ADC + PreAmp + ピエゾセンサーによる高品質音データ取得。回転機器等の製造装置から異常兆候を検出

**データ基盤設計**  
POC段階ではSQLite3で迅速な検証、本番ではPostgreSQL/TimescaleDBで大規模時系列データ処理。適材適所の技術選定を重視

**アルゴリズム開発**  
相同性検索（ゲノム）、材料特性予測（高分子）、異常検知（製造プロセス・音響信号）

### 技術スタック

- **解析・AI**: Python（NumPy/Pandas/scikit-learn/librosa）、機械学習モデルの実装
- **信号処理**: DSP、FFT、ウェーブレット変換、音響特徴量抽出
- **バックエンド**: Node.js（API/リアルタイム処理）、Ruby on Rails（Web アプリケーション）、Go、C/C++（高性能処理・数値計算・制御系）
- **フロント**: JavaScript/TypeScript、React/Next.js
- **データ基盤**: SQLite3（POC/エッジ）、PostgreSQL/TimescaleDB（本番）、Docker/Kubernetes
- **エッジ**: Raspberry Pi、高精度ADC&PreAmp選定、ピエゾセンサー選定
- **並列処理**: OpenMP、Go並行処理

---

## 研究プロジェクト

### 🧭 toorPIA（高次元時系列データ解析エンジン）
製造装置の管理パラメータをリアルタイム解析し、異常兆候を自動検出・原因を提示する技術の研究開発プロジェクト。

**研究内容**
- 予兆検知：統計的手法による異常兆候の早期発見
- 根因推定：原因となるセンサー・パラメータの自動特定
- 調整提案：制御パラメータの最適化案の生成
- 実装検証：CSV連携・GUI・軽量スクリプトによる実証実験

**技術スタック**  
Python API（信号処理・解析）、BFF (Node.js + React/Next.js)、PostgreSQL + TimescaleDB、Docker/Kubernetes

[→ GitHub: toorpia/toorpia](https://github.com/toorpia/toorpia)

### 🔊 音響ベース予兆検知システム
回転機器等の製造装置から音データを取得し、異常兆候を検出する研究プロジェクト。

**技術構成**
- **ハードウェア**: Raspberry Pi + 高精度ADC + PreAmp + ピエゾセンサー
- **信号処理**: DSP、FFT、STFT、Wavelet、スペクトログラム解析
- **データ管理**: SQLite3（エッジ）→ PostgreSQL（集約）
- **解析**: 正常音パターンからの乖離検出、周波数特徴の時系列変化追跡

**実証内容**
- ベアリング劣化の早期検知
- モーター異常音の分類
- 振動パターンの可視化と異常判定

### 🪶 Local LLM Analysis
ローカル大規模言語モデルの内部表現を解析し、命題間の距離・バイアス構造を可視化する実験的研究プロジェクト。

[→ GitHub: toorpia-labs/local-llm-analysis](https://github.com/toorpia-labs/local-llm-analysis)

---

## 研究の歩み（Chronology）

### 2012-現在：製造業予兆検知（toor）
30年の経験を結集し、製造現場の「止まらない」を実現する技術開発。プロセスパラメータと音響信号の両面からアプローチ。

### 2006-2012：知財システム(ベンチャー)
知財管理の複雑性をデータ基盤で解決。技術とビジネスの統合。

### 1998-2006：ゲノム・材料DB(三菱総研)
国際ヒトゲノムプロジェクトでの大規模データ処理、高分子材料データベースでの構造化データ設計。

### 1995-1998：化学プラント(東燃化学)
PP/PEポリマー製造プラントでのプロセス設計・データ解析。製造業データエンジニアリングのルーツ。

---

## 特許・論文

### 特許（米国）

**多次元相関データ抽出装置および方法**  
US Patent 10,353,892 (2019)  
多次元空間における相関サブセット抽出と特徴要素発見の手法

**状態判定装置および方法**  
US Patent 10,621,028 (2020)  
デバイスデータの時系列結合と類似度ベース状態分析

**データ解析装置および方法**  
US Patent Application 20160109355  
周波数スペクトルを用いた類似度指標によるセグメント解析

**文書検索装置および方法**  
US Patent 8,818,979 (2014)  
二次元マップ上での対話的文書検索とクエリベクトル結合

**解析装置およびシステム**  
US Patent Application 20210232567  
参照マップへの新規データプロッティング手法

**情報表示方法および装置**  
US Patent Application 20170213249  
検索サービスにおける関連性を明確化した広告表示

### 学術論文

**ゲノム解析**
- DIGIT: a novel gene finding program by combining gene-finders. T. Yada, T. Takagi, Y. Totoki, Y. Sakaki, Y. Takaeda. *Pacific Symposium on Biocomputing*, 2003

**高分子溶液の光散乱・核磁気緩和研究(1993-1997)**
- Dynamic depolarized light scattering and nuclear magnetic relaxation studies of isotactic oligo- and poly(methyl methacrylate)s in dilute solution. *Macromolecules*, 1997, 30(9), 2751-2758
- Dynamic depolarized light scattering and nuclear magnetic relaxation studies of oligo- and poly(methyl methacrylate)s in dilute solution. *Macromolecules*, 1995, 28(3), 682-693
- Mean-square optical anisotropy of isotactic oligo- and poly(methyl methacrylate)s in dilute solution. *Macromolecules*, 1995, 28(12), 4167-4172
- Dynamic depolarized light scattering and nuclear magnetic relaxation studies of oligo- and polystyrenes in dilute solutions. *Macromolecules*, 1994, 27(15), 4248-4258
- On the correlation between the negative intrinsic viscosity and the rotatory relaxation time of solvent molecules in dilute polymer solutions. *Macromolecules*, 1993, 26(25), 6891-6896
- Mean-square optical anisotropy of oligo- and poly(methyl methacrylate)s in dilute solutions. *Macromolecules*, 1993, 26(15), 3742-3749

---

## 研究姿勢

**現場主義**  
理論よりも"運用し続けられる構造"の探求。化学プラントからゲノム解析、製造装置まで、常に現場に立つ。

**適材適所の技術選定**  
過剰設計を避け、小さく始めて速く回す。

**批判的思考の重視**  
反対意見を組み込み、リスクを早期顕在化。30年の失敗と成功から学んだ姿勢。

**学びの循環**  
技術を現場に戻し、現場から再び学び取る。教育と実務を相互に強化。教育・実務・研究の三位一体循環を重視している。

**個人の公的声明**  
個人のエンジニアは企業構造に消費されるのではなく、真に必要とされる現場に直接価値を届けるべきだと考えています。

---

## 連絡先

**GitHub**: [github.com/takaeda](https://github.com/takaeda)  
**Email**: [takaeda@gmail.com](mailto:takaeda@gmail.com)  
**所在**: 日本

*このサイトは個人の研究活動・教育活動を紹介する非商用サイトです*

---

<small>© 2025 Yoshio Takaeda | Personal Research Portfolio</small>
