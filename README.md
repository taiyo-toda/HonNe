![本音SNS](https://img.shields.io/badge/本音SNS-v1.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

# 本音で語ろうぜ！

> **🏆 TrackJobハッカソン成果物**  
> **⚠️ 現在はモックアップ段階です。サービスは稼働していません。**

## 💡 プロジェクト概要

### 世論、風潮に対するホンネを吐き出せる、完全匿名の短文投稿SNS

みんなが心の奥で思っているけれど表立って言えない**本音**を投稿・共有できる完全匿名の短文投稿SNSです。

建前社会に疲れた現代人が、素直な気持ちを吐き出せる居場所を提供します。

---

## ✨ 機能一覧

- **📝 本音投稿**: 匿名で率直な意見を投稿
- **👥 共感機能**: いいねで「わかる！」を表現
- **🏷️ カテゴリー分類**: 仕事・恋愛・家族・お金・その他で整理
- **🔍 話題検索**: キーワードで気になるトピックを発見

---

## 🛠️ 使用技術

* **フロントエンド**: [HTML, CSS, JavaScript]
* **バックエンド**: [JavaScript]
* **データベース**: [JSON]
* **その他**: [GitHub, Claude, Copilot]

---

## 👨‍👩‍👧‍👦 チームメンバー

| 役割 | 名前 | GitHubアカウント |
|:---:|:---:|:---:|
| プロジェクトリーダー | 小川遥生(おがわはるき) | @haruki-prog(https://github.com/haruki-prog) |
| デベロッパー/プランナー | 檜垣洸太(ひがきこうた) | @higakota(https://github.com/higakota) |
| プロダクトオーナー/UI・UX | 戸田太陽(とだたいよう) | @taiyo-toda(https://github.com/taiyo-toda) |

---

## 🚀 実行方法
このプロジェクトを自分のPCで動かすための手順を説明します。

## 1. プロジェクトファイルを取得する
git clone https://github.com/taiyo-toda/HonNe.git
cd HonNe

## 2. 必要なファイルが揃っているか確認する
プロジェクトフォルダに以下のファイルがあることを確認してください：
HonNe/
├── simple.html      # メインのHTMLファイル
└── topics.json      # トピックデータファイル

## 3. ローカルサーバーを起動する
重要: このアプリはJSONファイルを読み込むため、ローカルサーバーでの実行が必要です。

### 方法1: Pythonを使用

### Python 3の場合
* python -m http.server 8000

### Python 2の場合
* python -m SimpleHTTPServer 8000

### 方法2: Node.jsを使用

* npx（Node.js付属）を使用
npx http-server -p 8000

* または、http-serverをインストール
npm install -g http-server
http-server -p 8000

### 方法3: Live Server（VS Code拡張機能）（推奨）

VS Codeで「Live Server」拡張機能をインストール
simple.htmlを右クリック → 「Open with Live Server」

## 4. ブラウザでアクセスする
サーバー起動後、以下のURLにアクセス：

## 5. 動作確認
正常に動作している場合：

✅ トピック一覧が表示される
✅ 新しいトピックを作成できる
✅ 投稿の追加・いいね・削除ができる
✅ カテゴリーフィルターと並べ替えが機能する

## 📄 ライセンス

このプロジェクトは **MITライセンス** のもとで公開されています。

### 📋 利用条件
- ✅ **商用・非商用問わず自由に利用可能**
- ✅ **改変・再配布OK**
- ✅ **クレジット表記のみ必要**

### ⚠️ 注意事項

- 本プロジェクトはハッカソンの成果物です
- 現在はモックアップ段階のため、実用性に制限があります
- 商用利用時は動作保証いたしかねます

詳細は LICENCE をご確認ください。

### 🤝 チーム連絡先

本格的な商用利用やコラボレーションをご希望の場合：
- GitHub Issues での相談
- 各メンバーへの直接連絡

## 🏆 最後に

**「本音で語ろうぜ！」** はTrackJobハッカソンで生まれたアイデアです。

現在はモックアップ段階ですが、多くの人に共感していただければ、実際のサービス化を目指したいと考えています。

あなたの応援が、このプロジェクトを現実のものにする力になります！

**⭐ このアイデアが気に入ったら、ぜひスターをお願いします！**
