# 🎰 Pachinko Scraping Portfolio

## 🚀 プロジェクト概要
**目標**：パチンコ店の台データをスクレイピングしてCSV/Excelに保存するツールを開発する。  
**学習スタイル**：独学（Progate + 書籍 + 実践課題）、進捗と成果物をGitHubに記録。  

このリポジトリでは、初心者からスクレイピングツール完成までの成長プロセスをまとめています。  

---

## 🗓 学習ロードマップ
### 📍 基礎習得（Week 1–3）
- Progate Python I–VI を学習  
- `print` / `if` / `for` / `関数` / `リスト・辞書` を習得  
- 簡単な課題（電卓プログラム・CSV合計計算など）を作成  

### 📍 スクレイピング入門（Week 4–5）
- **requests** でWebページ取得  
- **BeautifulSoup** でHTML解析  
- 1店舗ページから台データ（機種名・台番・回転数・BB/RB・差枚など）を抽出  
- CSVに保存できる最小ツールを完成  

### 📍 応用・拡張（Week 6以降）
- 複数ページ（日付・ページネーション）の対応  
- 複数店舗のURLをループ処理  
- データの重複排除（キー：日付＋店舗＋台番）  
- pandasで集計・可視化（平均差枚のグラフ化など）  
- Excel出力＋タスクスケジューラで自動実行  

---

## 💻 使用技術
- 言語: Python 3.x  
- ライブラリ:  
  - `requests`（Webリクエスト）  
  - `beautifulsoup4`（HTML解析）  
  - `pandas`（データ処理・CSV/Excel保存）  
  - `lxml`（HTMLパーサ）  

---

## 📊 成果物（予定）
1. **最小スクレイピングツール**（1ページ→CSV保存）  
2. **複数ページ対応ツール**（日付や店舗ごとに収集）  
3. **集計・可視化ツール**（平均差枚をExcelやグラフで出力）  

---

## ✍️ 学びと工夫
- Progateを通して基礎を固めた上で、実際に「欲しいデータを取る」課題に取り組むことで、学習の定着を意識。  
- ただコードを書くのではなく、**安全なスクレイピング**（robots.txtやアクセス負荷の配慮）を重視。  
- 成果物は「そのまま使えるツール」ではなく、「学習の記録＋応用可能な雛形」として公開。  

---

## 📈 今後の展望
- 動的サイト対応（Selenium, Playwrightの導入）  
- ChatGPT APIと組み合わせて「台データの自動要約」  
- BIツール（Tableau/Power BI）との連携によるデータ分析  

---

## 📂 リポジトリ構成（例）
pachinko-scraping-portfolio/
│
├─ basics/ # Progate演習や基礎課題
│ └─ calculator.py
│ └─ csv_sum.py
│
├─ scraping/ # スクレイピング練習コード
│ └─ single_page.py
│ └─ multi_page.py
│
├─ analysis/ # データ加工・可視化
│ └─ aggregate.py
│ └─ plot_diff.py
│
├─ data/ # 出力データ（例：CSV/Excel）
│
└─ README.md # この説明ファイル
