# RSS関数仕様書インデックス

楽天証券MARKETSPEED II RSSの全関数仕様書

**総関数数**: 38

## カテゴリ別一覧

### Account関連 (8関数)

- [RssBuyingPower](functions/RssBuyingPower.md) - 買付余力情報取得
- [RssCapacityList](functions/RssCapacityList.md) - 現物建玉リスト取得
- [RssExecutionList](functions/RssExecutionList.md) - 約定情報リスト取得
- [RssFOPCapacityList](functions/RssFOPCapacityList.md) - 先物オプション建玉リスト取得
- [RssFOPExecutionList](functions/RssFOPExecutionList.md) - 先物オプション約定リスト取得
- [RssFOPOrderList](functions/RssFOPOrderList.md) - 先物オプション注文リスト取得
- [RssFOPPositionList](functions/RssFOPPositionList.md) - 先物オプション建玉リスト取得
- [RssPositionList](functions/RssPositionList.md) - 建玉リスト取得

### Chart関連 (3関数)

- [RssChart](functions/RssChart.md) - チャートデータ取得
- [RssChartPast](functions/RssChartPast.md) - 過去チャートデータ取得
- [RssTrendSMA](functions/RssTrendSMA.md) - 移動平均トレンド取得

### Margin関連 (4関数)

- [RssMarginCloseOrder](functions/RssMarginCloseOrder.md) - 信用返済注文
- [RssMarginInfo](functions/RssMarginInfo.md) - 信用情報取得
- [RssMarginOpenOrder](functions/RssMarginOpenOrder.md) - 信用新規注文
- [RssMarginPower](functions/RssMarginPower.md) - 信用余力情報取得
- [RssMarginPositionList](functions/RssMarginPositionList.md) - 信用建玉リスト取得

### Market Data関連 (8関数)

- [RssFOPMarket](functions/RssFOPMarket.md) - 先物オプション時価情報取得
- [RssFOPMarketDes](functions/RssFOPMarketDes.md) - 先物オプション銘柄詳細取得
- [RssFXMarket](functions/RssFXMarket.md) - FX時価情報取得
- [RssIndexMarket](functions/RssIndexMarket.md) - 指数時価情報取得
- [RssMarket](functions/RssMarket.md) - 現物時価情報取得
- [RssMarketDes](functions/RssMarketDes.md) - 現物銘柄詳細取得
- [RssMarketHeader](functions/RssMarketHeader.md) - 市況ヘッダー情報取得
- [RssTickList](functions/RssTickList.md) - ティックデータリスト取得

### Order関連 (13関数)

- [RssCancelOrder](functions/RssCancelOrder.md) - 注文取消
- [RssFOPCancelOrder](functions/RssFOPCancelOrder.md) - 先物オプション注文取消
- [RssFOPCloseOrder](functions/RssFOPCloseOrder.md) - 先物オプション決済注文
- [RssFOPModifyOrder](functions/RssFOPModifyOrder.md) - 先物オプション注文訂正
- [RssFOPMultiCloseOrder](functions/RssFOPMultiCloseOrder.md) - 先物オプション一括決済注文
- [RssFOPMultiOpenOrder](functions/RssFOPMultiOpenOrder.md) - 先物オプション一括新規注文
- [RssFOPOpenOrder](functions/RssFOPOpenOrder.md) - 先物オプション新規注文
- [RssModifyOrder](functions/RssModifyOrder.md) - 注文訂正
- [RssOrderIDList](functions/RssOrderIDList.md) - 注文ID情報リスト取得
- [RssOrderList](functions/RssOrderList.md) - 注文リスト取得
- [RssOrderStatus](functions/RssOrderStatus.md) - 注文状況取得
- [RssStockOrder](functions/RssStockOrder.md) - 現物株式注文

### Utils関連 (2関数)

- [RssFOPCode](functions/RssFOPCode.md) - 先物オプションコード情報取得
- [RssFutInfo](functions/RssFutInfo.md) - 先物情報取得

## 関数名別索引（アルファベット順）

| 関数名 | 分類 | 説明 |
|--------|------|------|
| [RssBuyingPower](functions/RssBuyingPower.md) | Account | 買付余力情報取得 |
| [RssCancelOrder](functions/RssCancelOrder.md) | Order | 注文取消 |
| [RssCapacityList](functions/RssCapacityList.md) | Account | 現物建玉リスト取得 |
| [RssChart](functions/RssChart.md) | Chart | チャートデータ取得 |
| [RssChartPast](functions/RssChartPast.md) | Chart | 過去チャートデータ取得 |
| [RssExecutionList](functions/RssExecutionList.md) | Account | 約定情報リスト取得 |
| [RssFOPCancelOrder](functions/RssFOPCancelOrder.md) | Order | 先物オプション注文取消 |
| [RssFOPCapacityList](functions/RssFOPCapacityList.md) | Account | 先物オプション建玉リスト取得 |
| [RssFOPCloseOrder](functions/RssFOPCloseOrder.md) | Order | 先物オプション決済注文 |
| [RssFOPCode](functions/RssFOPCode.md) | Utils | 先物オプションコード情報取得 |
| [RssFOPExecutionList](functions/RssFOPExecutionList.md) | Account | 先物オプション約定リスト取得 |
| [RssFOPMarket](functions/RssFOPMarket.md) | Market Data | 先物オプション時価情報取得 |
| [RssFOPMarketDes](functions/RssFOPMarketDes.md) | Market Data | 先物オプション銘柄詳細取得 |
| [RssFOPModifyOrder](functions/RssFOPModifyOrder.md) | Order | 先物オプション注文訂正 |
| [RssFOPMultiCloseOrder](functions/RssFOPMultiCloseOrder.md) | Order | 先物オプション一括決済注文 |
| [RssFOPMultiOpenOrder](functions/RssFOPMultiOpenOrder.md) | Order | 先物オプション一括新規注文 |
| [RssFOPOpenOrder](functions/RssFOPOpenOrder.md) | Order | 先物オプション新規注文 |
| [RssFOPOrderList](functions/RssFOPOrderList.md) | Account | 先物オプション注文リスト取得 |
| [RssFOPPositionList](functions/RssFOPPositionList.md) | Account | 先物オプション建玉リスト取得 |
| [RssFutInfo](functions/RssFutInfo.md) | Utils | 先物情報取得 |
| [RssFXMarket](functions/RssFXMarket.md) | Market Data | FX時価情報取得 |
| [RssIndexMarket](functions/RssIndexMarket.md) | Market Data | 指数時価情報取得 |
| [RssMarginCloseOrder](functions/RssMarginCloseOrder.md) | Margin | 信用返済注文 |
| [RssMarginInfo](functions/RssMarginInfo.md) | Margin | 信用情報取得 |
| [RssMarginOpenOrder](functions/RssMarginOpenOrder.md) | Margin | 信用新規注文 |
| [RssMarginPositionList](functions/RssMarginPositionList.md) | Margin | 信用建玉リスト取得 |
| [RssMarginPower](functions/RssMarginPower.md) | Margin | 信用余力情報取得 |
| [RssMarket](functions/RssMarket.md) | Market Data | 現物時価情報取得 |
| [RssMarketDes](functions/RssMarketDes.md) | Market Data | 現物銘柄詳細取得 |
| [RssMarketHeader](functions/RssMarketHeader.md) | Market Data | 市況ヘッダー情報取得 |
| [RssModifyOrder](functions/RssModifyOrder.md) | Order | 注文訂正 |
| [RssOrderIDList](functions/RssOrderIDList.md) | Order | 注文ID情報リスト取得 |
| [RssOrderList](functions/RssOrderList.md) | Order | 注文リスト取得 |
| [RssOrderStatus](functions/RssOrderStatus.md) | Order | 注文状況取得 |
| [RssPositionList](functions/RssPositionList.md) | Account | 建玉リスト取得 |
| [RssStockOrder](functions/RssStockOrder.md) | Order | 現物株式注文 |
| [RssTickList](functions/RssTickList.md) | Market Data | ティックデータリスト取得 |
| [RssTrendSMA](functions/RssTrendSMA.md) | Chart | 移動平均トレンド取得 |

