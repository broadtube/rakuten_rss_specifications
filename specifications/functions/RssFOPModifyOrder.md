# RssFOPModifyOrder 完全仕様書

## 概要
**関数名**: RssFOPModifyOrder  
**カテゴリ**: 先物OP注文管理 (Futures & Options Order Management)  
**用途**: 先物OP訂正注文  

**説明**: 先物・オプション取引での既存注文を訂正します。価格や数量、執行条件の変更が可能です。

## 構文 (Syntax)

### Excel ワークシート関数
```excel
RssFOPModifyOrder(注文番号, 注文数量, 価格区分, 注文価格, 執行条件, 注文期日)
```

### VBA関数
```vb
RssFOPModifyOrder_V(注文番号, 注文数量, 価格区分, 注文価格, 執行条件, 注文期日)
```

## 使用例

### 注文価格の変更
```excel
=RssFOPModifyOrder("F2024050800001",1,1,38550,1,)
```

## バージョン情報
- RSS Version: 2.0
- 対応: Excel 2016以降
- 最終更新: 2024年