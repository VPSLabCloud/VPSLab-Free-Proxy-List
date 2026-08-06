# [VPSLab](https://vpslab.cloud/) 無料プロキシリスト

<!-- hy-mt2-i18n:start -->
[English](./README.md) | [中文](./README_zh-CN.md) | **日本語** | [Español](./README_es.md)
<!-- hy-mt2-i18n:end -->

[![banner](https://iili.io/BBrV4Vt.png "20％割引をゲット")](https://vpslab.cloud/)
> **無料で高速、かつ頻繁に更新されるプロキシリスト** — HTTP、HTTPS、SOCKS4、SOCKS5プロキシが15分ごとに更新されます。

世界中の無料プロキシサーバーの情報を継続的に更新し提供するリポジトリである**VPSLab Free Proxy List**へようこそ。ウェブスクレイピング、地理的制限の回避、または匿名ブラウジングにプロキシが必要な場合でも、こちらでしっかり対応いたします。

**最終更新日時:** `2026-08-06 08:38 UTC` | **ファイルの総数:** 16

# 厳格な制約事項
1. **構造の維持**：元の Markdown のデータ構造、インデント、見出しの階層、表、リンク、URL、バッジ、コードブロック、インラインコードを一切変更しないこと。
2. **選択的翻訳**：ユーザーに表示される可視的な自然言語の内容のみを翻訳すること。
3. **変更禁止**：コードタグ、キー名、変数プレースホルダー（{{var}}、${var}、%s、%d など）、コマンド例、ファイルパス、プロジェクト名、API名、パッケージ名、モデル名、識別子、コード記号を翻訳したり変更したりすることは**厳禁**である。背景情報に既に対応する訳名が記載されている場合を除く。
4. 用語、スタイル、固有名詞の翻訳は、与えられた背景情報と一致させること。

## 🚀 なぜVPSLab無料プロキシリストを選ぶのか？

- **⚡ 15分ごとに更新** — GitHub上で最も頻繁に更新されるプロキシリストの一つです。  
- **🌍 世界中からのサーバー** — 世界中のあらゆる国や地域からのプロキシが揃っています。  
- **🔒 複数のプロトコル対応** — HTTP、HTTPS、SOCKS4、SOCKS5に加え、エリートプロキシ、匿名プロキシ、トランスペアレントプロキシも利用可能。  
- **🛡️ アノニマシティレベルの指定** — ご自身の用途に合わせて、エリートプロキシ、匿名プロキシ、トランスペアレントプロキシから選択可能。  
- **👨‍💻 開発者に優しい設計** — スクリプトやツールに簡単に組み込める、原始ファイルのURLが提供されています。  
- **🆓 完全無料** — 登録不要、APIキー不要、利用制限なし。  
- **⭐ コミュニティによって支えられている** — このリポジトリに星を付けて、毎日無料プロキシを利用している何千人もの開発者の仲間入りをしましょう。

---

## 🌟 サポートの意を示しましょう！

このプロジェクトが役立ったと感じたら：
- GitHubで**星マークを付けて**ください ⭐ — そうすることで、より多くの人がこのリポジトリを見つけられるようになります。
- 友人や同僚、ソーシャルメディアを通じてこのリポジトリを**共有して**ください。
- アップデートや新機能の通知を受け取るために、リポジトリを**フォロー**してください 👁️。

---

## 💡 プロキシファイル一覧

**最終更新日時:** `2026-08-06 08:38 UTC`

| ファイル | プロトコル | SSL | 匿匿名度 | 数量 |
|------|----------|-----|-----------|-------|
| [📄 http_all.txt](./http_all.txt) | `http` | `all` | `all` | **796** |
| [📄 http_ssl.txt](./http_ssl.txt) | `http` | `yes` | `all` | **263** |
| [📄 http_nossl.txt](./http_nossl.txt) | `http` | `no` | `all` | **536** |
| [📄 http_elite.txt](./http_elite.txt) | `http` | `all` | `elite` | **237** |
| [📄 http_anonymous.txt](./http_anonymous.txt) | `http` | `all` | `anonymous` | **38** |
| [📄 http_transparent.txt](./http_transparent.txt) | `http` | `all` | `transparent` | **522** |
| [📄 http_ssl_elite.txt](./http_ssl_elite.txt) | `http` | `yes` | `elite` | **111** |
| [📄 http_ssl_anonymous.txt](./http_ssl_anonymous.txt) | `http` | `yes` | `anonymous` | **9** |
| [📄 socks4_all.txt](./socks4_all.txt) | `socks4` | `all` | `all` | **236** |
| [📄 socks5_all.txt](./socks5_all.txt) | `socks5` | `all` | `all` | **371** |
| [📄 all_proxies.txt](./all_proxies.txt) | `all` | `all` | `all` | **1398** |
| [📄 all_elite.txt](./all_elite.txt) | `all` | `all` | `elite` | **836** |
| [📄 all_anonymous.txt](./all_anonymous.txt) | `all` | `all` | `anonymous` | **38** |
| [📄 all_transparent.txt](./all_transparent.txt) | `all` | `all` | `transparent` | **527** |
| [📄 all_ssl.txt](./all_ssl.txt) | `all` | `yes` | `all` | **866** |
| [📄 all_ssl_elite.txt](./all_ssl_elite.txt) | `all` | `yes` | `elite` | **713** |

---

## 🛠 使用方法

`curl` を使って直接プロキシリストをダウンロードでき、登録は不要です。

### HTTPプロキシ（全種類）
```bash
curl -sL https://raw.githubusercontent.com/VPSLabCloud/VPSLab-Free-Proxy-List/main/http_all.txt -o http_all.txt
```

### HTTPプロキシ（SSL/HTTPSのみ）
```bash
curl -sL https://raw.githubusercontent.com/VPSLabCloud/VPSLab-Free-Proxy-List/main/http_ssl.txt -o http_ssl.txt
```

### HTTP Elite Proxies（最も匿名性が高い）
```bash
curl -sL https://raw.githubusercontent.com/VPSLabCloud/VPSLab-Free-Proxy-List/main/http_elite.txt -o http_elite.txt
```

### HTTP匿名プロキシ
```bash
curl -sL https://raw.githubusercontent.com/VPSLabCloud/VPSLab-Free-Proxy-List/main/http_anonymous.txt -o http_anonymous.txt
```

### SOCKS4プロキシ
```bash
curl -sL https://raw.githubusercontent.com/VPSLabCloud/VPSLab-Free-Proxy-List/main/socks4_all.txt -o socks4_all.txt
```

### SOCKS5プロキシ
```bash
curl -sL https://raw.githubusercontent.com/VPSLabCloud/VPSLab-Free-Proxy-List/main/socks5_all.txt -o socks5_all.txt
```

### すべてのプロキシ（すべてのプロトコル）
```bash
curl -sL https://raw.githubusercontent.com/VPSLabCloud/VPSLab-Free-Proxy-List/main/all_proxies.txt -o all_proxies.txt
```

### すべてのエリートプロキシ
```bash
curl -sL https://raw.githubusercontent.com/VPSLabCloud/VPSLab-Free-Proxy-List/main/all_elite.txt -o all_elite.txt
```

---

## 🔍 プロキシの種類について

| タイプ | 説明 | 適している用途 |
|------|-------------|----------|
| **HTTP** | 標準のウェブプロキシ | 一般的なブラウジング、スクレイピング |
| **HTTPS/SSL** | 暗号化されたHTTPプロキシ | 安全な接続、HTTPSサイト |
| **SOCKS4** | 低レベルなTCPプロキシ | 迅速なトンネリング、古いアプリケーション |
| **SOCKS5** | 認証をサポートする高度なプロキシ | テーラント利用、SSHトンネリング、ゲーム |
| **Elite** | IPアドレスを完全に隠蔽 | 最高度の匿名性 |
| **Anonymous** | IPアドレスは隠蔽されるがプロキシ使用が判明 | バランスの取れた匿名性 |
| **Transparent** | 実際のIPアドレスが公開される | キャッシング、コンテンツフィルタリング |

---

## ⚡ VPSLab Cloud Hostingによって提供されています

このリポジトリは、開発者、スクレイパー、企業向けに構築された高性能なVPSホスティングサービスである**[VPSLab Cloud](https://vpslab.cloud)**によって管理・運営されています。

### なぜVPSLabでプロキシツールをホストするのか？
- 🚀 非常に高速なI/Oを実現する**NVMe SSD**ストレージ
- 🌍 世界中にある**複数のリージョン**
- 🔒 **DDoS対策**が標準で搭載
- 💰 手頃な価格 — VPSプランは月額わずか$Xから
- ⚙️ **完全なルートアクセス** — 好きなものを何でもデプロイ可能
- 🕐 **99.9%の稼働時間保証SLA**

👉 **[vpslab.cloudでVPSを入手する](https://vpslab.cloud)** ことで、ご自身のプロキシスクレイパー、ボット、またはツールを24時間365日稼働させることができます。

---

## 📣 最新情報をチェックしよう

- 👁️ 15分ごとにこのリポジトリを**フォロー**し、最新情報をリアルタイムで確認しましょう  
- ⭐ プロジェクトをブックマークし、サポートするには**星マーク**を付けてください  
- 🍴 自分だけのカスタマイズされたプロキシリストを作成するには**フォーク**してください  
- 💬 **ディスカッション**セクションでは、アイデアや利用事例、問題点などを共有できます

---

## 🏆 用途例

- **ウェブスクレイピング** — レート制限やブロックを避けるためにプロキシを切り替える  
- **SEOツール** — 複数のIPから検索エンジンのデータを収集する  
- **市場調査** — 地理的に制限されたコンテンツや価格情報にアクセスする  
- **プライバシー保護** — 実際のIPを開示せずに匿名で閲覧する  
- **テスト** — 異なる場所からアプリやウェブサイトをテストする  
- **自動化** — ボットや自動化スクリプトを動作させる

---

## 📢 広めてください

このプロジェクトの発展にご協力ください：
- 🐦 Twitterで投稿し、私たちをタグ付けしてください
- 📚 ブログ記事やチュートリアルで取り上げてください
- 📢 Reddit、HackerNews、Discordといったフォーラムでおすすめしてください

---

## ⚠️ 免責事項

これらのプロキシリストは、**情報提供および教育目的**でのみ提供されています。プロキシは公開されているソースから収集されたものであり、必ずしも正常に動作したり、安全だったり、プライバシーが保護されていたりするとは限りません。VPSLabは、いかなる違法または不正な活動も奨励したり支援したりしません。ご自身の責任において、かつご利用の地域の法律に従ってご使用ください。

---

*⭐ もしこのプロジェクトがあなたの時間を節約できたら、ぜひリポジトリに星マークを付けてください。わずか1秒で、何千人もの開発者がこのプロジェクトを見つけやすくなります。*
