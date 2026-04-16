# 量子コンピューティング I（2026年度 春学期）

慶應義塾大学 理工学部 情報工学科  
担当：佐藤貴彦

量子コンピュータ・量子インターネットの基礎を、Qiskitを使った演習を通じて学ぶ講義です。  
スライド資料は K-LMS で配布します。このリポジトリには演習用ノートブックを掲載します。

## 環境セットアップ

### 推奨：Google Colab（インストール不要）

1. 各ノートブックを開く
2. 先頭のセットアップセルを毎回実行する

### ローカル環境で動かしたい場合

```bash
pip install qiskit[visualization] qiskit-aer
```

- Python 3.10 以上
- VSCode + Jupyter 拡張がおすすめ
- 環境構築は各自で対応してください

## ノートブック一覧

| 回 | ファイル | 内容 |
|----|--------|------|
| #1 | `20260409_Setup.ipynb` | Qiskitインストール確認、量子コイントス、ベル状態 |
| #2 | `20260416_Basics1.ipynb` | １量子ビットゲート、２量子ビットゲート、量子もつれ |

※ 各回のノートブックは講義の進行に合わせて追加されます。

## IBM Quantum 実機について

- #5 以降の演習で IBM Quantum の実機を使用します
- IBM Quantum アカウントの作成は #4 終了時に案内します
- #1〜#4 はシミュレータのみで進められます

## 参考資料

- [IBM Quantum Learning](https://learning.quantum.ibm.com/)（英語）
- [IBM Quantum Platform 教材 日本語訳](https://quantum-tokyo.github.io/introduction/iqp_documents.html)
- [量子インターネット解説（研究室Webページ）](https://sites.google.com/view/satoh-quantum-lab/qi)

## 連絡先

質問・不具合報告は K-LMS の掲示板へお願いします。
