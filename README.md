# designflow_handson

## 本リポジトリについて

京都大学工学部情報学科 [計算機科学実験及演習３（ハードウェア）](https://isle3hw.kuis.kyoto-u.ac.jp)  
[「CADツールを用いた設計フロー」](https://isle3hw.kuis.kyoto-u.ac.jp/designflow2024.pdf) ハンズオンのQuartusプロジェクトを置いています．いわば正解データですので，実習を進める際の参考にしてください．

## 試行環境

- Windows 10 Pro
- Intel Quartus Prime 17.1 Lite Edition
- ModelSim Intel FPGA Starter Edition 10.5b
- Intel Core i7-7660U @ 2.50GHz / メモリ16.0 GB
- ターゲット：PowerMedusa MU500-RX/RK (Cyclone IV EP4CE30F23I7N)

## ブランチ名

下記の通りのブランチ名が資料P.14の目次の内容に対応しています．  
masterにはマージしていませんので，`git checkout`等で適宜切り替えてください．

- `a_p15-18`: 新規プロジェクトの作成と設定
- b_p19: (branch無し)論理回路の設計
- `c_p20-22`: HDLコードの作成（Verilog HDLの例）
- `d_p23-26`: コンパイル
- e_p27-30: (branch無し)タイミング制約の設定（参考）
- `f_p31-40`: シミュレーション
- `g_p41-43`: 入出力ピンの割当て
- `h_p44-48`: FPGAへの回路の書き込み

## gitignoreについて

本リポジトリではあえて`.gitignore`を整備していません．

[実験3HW WebページのFAQ](https://isle3hw.kuis.kyoto-u.ac.jp/faq.html#gitignore)に掲載しているものを参考にして，ご自身の環境と使い勝手に合わせて，適宜カスタマイズして（導入課題およびプロセッサ設計演習のリポジトリでも）使うと良いでしょう．


## ライセンス

[MIT License](LICENSE)
