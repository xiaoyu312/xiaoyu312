[简体中文](README.md) · [English](README.en.md) · **日本語**

# はじめまして、xiaoyu312 です

AI を使ってアイデアをプロダクトにしています。特に、EC とコンテンツ制作の仕事を進めやすくするツールに取り組んでいます。

[FateClear を試す · 無料の命式作成と解説](https://fateclear.com) · [X をフォロー](https://x.com/liu_xiaoyu27334)

## 代表的なプロジェクト

- [Pianchang · ソースと使い方](https://github.com/xiaoyu312/pianchang)：素材の検索、プレビュー、編集への引き継ぎ。**ソース公開、検証中。**
- [AutoClick · ソースと使い方](https://github.com/xiaoyu312/autoclick)：Web ページの対象を選び、指定した間隔でクリック。**ソース公開の実験版。**
- [AI Workflow Skills · 一覧と使い方](SKILLS.ja.md)：制作・運用・導入を支える 11 のワークフロー。**指示文を公開、生成品質は未検証。**
- [Creator Operations · ソースと使い方](https://github.com/xiaoyu312/creator-operations)：サンプル提供、日程、共同作業の引き継ぎ。**公開ソースと架空データのローカルデモ。**

<details>
<summary>全プロジェクトと検証範囲</summary>

実際の課題から出発し、繰り返し作業、散在するデータ、複雑な手順を使いやすい形に整理しています。ここでは、自作のシステム、ツール、Skills を紹介します。

## 目的からプロジェクトを探す

| やりたいこと | 最初に見るプロジェクト |
| --- | --- |
| ライブ配信、クリエイターとの協業、コンテンツ制作の作業を整理する | [Live Growth OS](https://github.com/xiaoyu312/live-growth-os) · [Creator Operations](https://github.com/xiaoyu312/creator-operations) · [Pianchang](https://github.com/xiaoyu312/pianchang) |
| 操作権限のある Web ページで同じ操作を繰り返す | [AutoClick](https://github.com/xiaoyu312/autoclick) |
| 自分のプロジェクトで時刻変換や暦データを使う | [時刻計算ライブラリ](https://github.com/xiaoyu312/fateclear-solar-time) · [暦データセット](https://github.com/xiaoyu312/fateclear-calendar-data) |
| AI アシスタントに再利用できる作業手順を渡す | [11 個の Skills 一覧](SKILLS.ja.md) |

各リポジトリにソース、使い方、検証範囲を記載しています。ソースの公開は、オンラインデモの提供や本番運用の検証完了を意味しません。

## Web プロダクト

### FateClear · 拨云

生年月日・出生時刻に基づく命式の作成と解説を無料で利用できる Web サイトです。有料の AI チャット機能は計画中です。このプロフィールではサイトへのリンクを案内し、ローカルのアプリケーションソースは公開していません。

[FateClear を開く →](https://fateclear.com)

## 開発中のシステム

### Live Growth OS

**ライブ配信運営 · ソース公開の実験版**

ライブ配信の指標、AI の提案、実行した対応、その後のフィードバックをつなぎ、運営上の課題と次のアクションを追いやすくするシステムです。

整理したソースを公開し、限定的なオフラインチェックを実施しています。クリーンインストール、全体の型チェック、テスト一式、ビルド、起動は未検証です。実際の OAuth 連携、継続的なデータ連携、Windows 上での検証も残っています。公開オンラインデモはありません。

[公開プロジェクトと検証範囲を見る →](https://github.com/xiaoyu312/live-growth-os)

### 片场 / Pianchang

**コンテンツ制作 · ローカルおよび内部での検証段階**

素材の検索、プレビュー、注釈、編集担当への引き継ぎをつなぐ、コンテンツ制作向けのワークスペースです。

NAS、Windows、剪映との連携は未検証です。公開デモは提供していません。

[公開プロジェクトを見る →](https://github.com/xiaoyu312/pianchang)

### 达播 / Creator Operations

**クリエイターとの協業 · 公開ソースと架空データのローカルデモ**

クリエイターとの協業に必要なサンプル提供、日程、担当間の引き継ぎを整理し、進行に必要な情報をまとめるワークスペースです。

公開時の検証記録では、主アプリと Creator Assistant の合計 318 件のテスト、フロントエンドとバックエンドの型チェック、Vite のフロントエンドビルドが通過しています。公開版は、再起動するとリセットされる架空データのローカルデモが標準です。完全な企業向け AppModule、ワークブックの永続化、データベースのマイグレーションは含みません。クリーンインストール、実際のブラウザー操作、本番デプロイは未検証です。

[公開プロジェクトと起動方法を見る →](https://github.com/xiaoyu312/creator-operations)

## 実用ツール

### AutoClick DOM

**ブラウザーとデスクトップの自動操作 · 実験版**

Web ページ上の対象を選び、指定した間隔でクリックします。Chrome/Edge 拡張機能と Electron デスクトップ版のソース、ローカルチェックとビルド用のコマンドを公開しています。

ビルド済みアプリやストア公開の記録は含みません。拡張機能のインストール、Electron の起動、Windows 向けパッケージ化、実際のサービス上での動作、長時間の実行は未検証です。

[公開プロジェクトを見る →](https://github.com/xiaoyu312/autoclick)

### 千川ライブダッシュボード収集ツール

**実験版 · ライブ配信運営**

指定した間隔で配信データを整理し、配信担当者のスケジュールと対応付けて CSV に出力する、振り返りを支援するツールです。

実際の Windows 環境におけるサービス画面と障害時の動作は未検証です。

[プロジェクトを見る →](https://github.com/xiaoyu312/qianchuan-live-board-tool)

### ECK Order Customer Matcher

**ベータ版 · EC 作業の効率化**

注文を整理し、顧客区分を判定して結果を出力するローカルツールです。注文分析と結果の確認を支援します。

機密情報を除いた一部の検証シナリオでは動作を確認済みです。Windows 実機と実際のサービスを通した一連の操作は、引き続き検証が必要です。

[プロジェクトを見る →](https://github.com/xiaoyu312/eck-order-customer-matcher)

## 開発者向けライブラリとオープンデータ

### fateclear-solar-time

**時刻計算 · TypeScript / MCP · MIT**

時計の時刻と経度から真太陽時を計算し、二十四節気の時刻や中国の 1986–1991 年の夏時間状態を取得できます。自分のアプリや AI アシスタントにこれらの計算を組み込みたい開発者向けです。

[API、MCP 設定、精度の範囲を見る →](https://github.com/xiaoyu312/fateclear-solar-time)

### fateclear-calendar-data

**暦データ · CSV / JSON · CC BY 4.0**

1900–2100 年の節気、日ごとの干支と旧暦の日付、中国の夏時間表を提供します。大きなデータファイルは Release から取得するか、リポジトリの手順で生成できます。データの利用には出典表示が必要で、生成スクリプトは別途 MIT で公開されています。

[ダウンロード、フィールド、出典表示の要件を見る →](https://github.com/xiaoyu312/fateclear-calendar-data)

## Skills とワークフロー

整理した 11 個の汎用版を [AI Workflow Skills](https://github.com/xiaoyu312/ai-workflow-skills) で公開しています。脚本とコピー、動画制作、EC の振り返り、運営画面の設計、プロダクトの導入支援、個人の計画に対応します。

公開版には、再配布の対象外とした講座・書籍の原文や非公開データを含みません。元の非公開版の方法体系全体を再現するものでもありません。各パッケージの機能とチェック範囲はリポジトリで確認できます。モデル出力の品質と実際のサービス上での効果は未検証です。

[Skills 一覧を見る →](SKILLS.ja.md)

![xiaoyu312：AI プロダクト、EC、コンテンツ制作のワークフロー](assets/hero.svg)

</details>

<details>
<summary>連絡先</summary>

プロダクトを試すなら、無料の [FateClear の命式作成と解説](https://fateclear.com) をどうぞ。AI プロダクトや実用ツールについては、[X](https://x.com/liu_xiaoyu27334) で気軽に声をかけてください。

[Web サイト · FateClear](https://fateclear.com) · [X · @liu_xiaoyu27334](https://x.com/liu_xiaoyu27334) · [メール](mailto:a18565517703@gmail.com)

<details>
<summary>WeChat で連絡する</summary>

<img src="assets/wechat-qr.png" alt="WeChat 連絡用 QR コード" width="220" />

[QR コードを大きく表示](assets/wechat-qr.png)

</details>

</details>
