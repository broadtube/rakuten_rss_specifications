# rakuten_rss_specifications

楽天証券 MARKETSPEED II RSS関数の非公式仕様書集

## 概要

このプロジェクトは、楽天証券のMARKETSPEED II RSSシステムで利用可能な関数について、個人的に調査・整理した非公式の仕様書集です。Excel/VBAでの金融データ取得や注文処理の自動化に役立つ情報をまとめています。

**重要:** これは非公式かつ個人的なプロジェクトです。楽天証券による公式なドキュメントではありません。

## 特徴

- **38個のRSS関数**をカバー
- 詳細なパラメータ仕様と使用例
- 実際の戻り値形式の解説
- エラーハンドリング情報
- 実用的なコード例

## 対象関数カテゴリ

### 注文管理
- 現物株式注文（RssStockOrder）
- 信用取引注文（RssMarginOpenOrder, RssMarginCloseOrder）
- 注文訂正・取消（RssModifyOrder, RssCancelOrder）
- 注文一覧・状況確認（RssOrderList, RssExecutionList）

### 市場データ
- 株価情報（RssMarket, RssMarketDes）
- チャートデータ（RssChart, RssChartPast, RssTrendSMA）
- 指数・為替（RssIndexMarket, RssFXMarket）
- 歩み値（RssTickList）

### 先物オプション
- FOP注文（RssFOPOpenOrder, RssFOPCloseOrder等）
- FOP市場データ（RssFOPMarket, RssFOPMarketDes）
- FOP建玉管理（RssFOPPositionList）

### 口座・資産情報
- 余力情報（RssCapacityList, RssBuyingPower等）
- 保有証券（RssPositionList）
- 建玉一覧（RssMarginPositionList）

## ファイル構成

```
specifications/
└── functions/
    ├── RssStockOrder.md
    ├── RssMarginOpenOrder.md
    ├── RssMarket.md
    └── ... (全38個の関数仕様書)
```

## 使用方法

各関数の仕様書には以下の情報が含まれています：

- **概要**: 関数の目的と用途
- **構文**: Excel版・VBA版の記述方法
- **パラメータ**: 詳細な引数説明
- **戻り値**: 成功時・失敗時の出力例
- **使用例**: 実践的なコード例
- **注意事項**: 制限事項や注意点

## 注意事項

1. **非公式性**: このドキュメントは楽天証券の公式資料ではありません
2. **正確性**: 情報の正確性は保証されません。実際の利用前に公式資料で確認してください
3. **責任**: 本情報の使用による損失等について作者は一切の責任を負いません
4. **最新性**: RSSシステムの仕様変更により情報が古くなる可能性があります

## 対象環境

- MARKETSPEED II RSS Version 2.0
- Microsoft Excel 2016以降
- VBA対応

## ライセンス

MIT License

## 免責事項

- この仕様書は個人的な調査に基づく非公式な資料です
- 楽天証券との関係はありません
- 投資は自己責任で行ってください
- 本資料の利用により生じた損害について作者は責任を負いません

## 参考資料

- 楽天証券 MARKETSPEED II 公式サイト
- RSS関数オンラインヘルプ（楽天証券提供）

---

**注意**: このプロジェクトは教育・研究目的で作成された非公式な資料集です。実際の取引では公式資料を参照し、自己責任で行ってください。