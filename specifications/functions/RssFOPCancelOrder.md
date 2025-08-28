# RssFOPCancelOrder 完全仕様書

## 概要
**関数名**: RssFOPCancelOrder  
**カテゴリ**: 先物OP注文管理 (Futures & Options Order Management)  
**用途**: 先物OP取消注文  

**説明**: 先物・オプション取引での既存注文を取り消します。未約定注文または一部約定注文の残り部分を取り消すことができます。

## 構文 (Syntax)

### Excel ワークシート関数
```excel
RssFOPCancelOrder(注文番号)
```

### VBA関数
```vb
RssFOPCancelOrder_V(注文番号)
```

## パラメータ詳細

| No | パラメータ名 | 必要性 | データ型 | 説明 |
|----|------------|--------|----------|------|
| 1 | 注文番号 | ● | string | 取消する注文の注文番号 |

## 使用例

### 注文の取消
```excel
=RssFOPCancelOrder("F2024050800001")
```

## 戻り値
成功時：取消受付番号  
失敗時：エラーコード（#VALUE!, #N/A等）

## バージョン情報
- RSS Version: 2.0
- 対応: Excel 2016以降
- 最終更新: 2024年