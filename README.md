# Code for Matsubara 🚀

[![Website](https://img.shields.io/badge/Official_Site-codeformatsubara.org-blue.svg?style=flat-square)](https://codeformatsubara.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)
[![Python 3.12+](https://img.shields.io/badge/Python-3.12+-3776AB.svg?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)

大阪府松原市のオープンデータを活用し、市民の力で地域をアップデートする非営利のシビックテック・プロジェクト「**Code for Matsubara**」の公式リポジトリです。

## 📖 Overview

**「テクノロジーとデザインの力で、地域をもっと便利で楽しくする」**

市役所が公開するオープンデータを利用し、真に価値のあるシステムやアプリケーションを自らの手（コード）で開発・無償提供することで、地域のDX（デジタルトランスフォーメーション）を草の根から推進します。

---

## ⚡ Active Projects

当コミュニティで開発・運用中の主要なオープンソース・プロジェクトです。

### 🔍 松原市議会 議事録AI検索くん
* **URL**: [https://matsubara.council-minutes-ai-search.jp/](https://matsubara.council-minutes-ai-search.jp/)
* **Description**: 松原市議会の膨大な議事録をRAG（検索拡張生成）技術を用いて高度に解析するシステム。Gemini AIをバックエンドに採用し、過去8年分（156MB以上）の議員発言からハイコンテキストな情報抽出と要約をリアルタイムに実現します。

### 📍 松原市 温故知新マップ
* **URL**: [http://map.codeformatsubara.org/](http://map.codeformatsubara.org/)
* **Description**: 松原市公式オープンデータ「まつばらいろはかるた」をベースにしたGIS連携Webアプリケーション。GPSを活用し、地域の文化財をシームレスに探索できる体験を提供します。

---

## 🛠 Architecture & Tech Stack

プロジェクトの特性に合わせ、モダンかつスケーラブルな技術スタックを採用しています。

### Frontend (Portal & GIS)
* **Languages**: HTML5 / CSS3 / JavaScript (ES6+)
* **Framework**: Tailwind CSS
* **Semantic Web**: JSON-LD (Schema.org) による構造化データ実装

### Backend & AI Core (AI Search Engine)
* **Runtime**: Python 3.12+
* **API Gateway**: FastAPI / Uvicorn (High-performance ASGI server)
* **LLM Engine**: Google Gemini (`google-genai` SDK)
* **Data Pipeline**: Playwright / HTTPX (Automated Headless Scraping)
* **Database**: SQLite3 (Metadata handling)

### Infrastructure & DevOps
* **Cloud Provider**: ConoHa VPS (Ubuntu Server)
* **Web Hosting**: GitHub Pages
* **Process Management**: `systemd` (Daemonization)
* **Security**: Let's Encrypt (SSL/TLS), Strict Security Group Optimization

---

## 💡 Development Policy

1. **Open Source First**: すべての成果物は原則公開され、誰でも再利用・貢献が可能です。
2. **Civic-Centric Design**: 開発者目線に偏らず、全市民が直感的に利用できるUI/UXを追求します。
3. **Data-Driven**: 行政の公式なオープンデータを信頼の根拠とし、情報の透明性を確保します。

---

## 👥 Community & Maintainer

本プロジェクトは、テクノロジーによる社会課題解決（**Tech for Good**）の理念に賛同する有志の市民エンジニアによって開発・維持されています。

* **Lead Maintainer**: Takafumi Maruyoshi (松原市議会議員 / シビックテックエンジニア)
* **GitHub Profile**: [@health-gear](https://github.com/health-gear)

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.
