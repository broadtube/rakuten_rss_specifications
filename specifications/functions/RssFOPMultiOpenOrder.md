# RssFOPMultiOpenOrder 完全仕様書

## 概要
**関数名**: RssFOPMultiOpenOrder  
**カテゴリ**: 先物OP注文管理 (Futures & Options Order Management)  
**用途**: 先物OP複数新規注文  

**説明**: 先物・オプション取引で複数銘柄の新規注文を一括で行います。効率的な注文執行により、複数ポジションの同時構築が可能です。

## 構文 (Syntax)

### Excel ワークシート関数
```excel
RssFOPMultiOpenOrder(発注ID, 発注トリガー, 注文データ範囲)
```

### VBA関数
```vb
RssFOPMultiOpenOrder_V(発注ID, 注文データ範囲)
```

## パラメータ詳細

| No | パラメータ名 | 必要性 | データ型 | 説明 |
|----|------------|--------|----------|------|
| 1 | 発注ID | ● | number | 複数注文を識別するID |
| 2 | 発注トリガー | ● | number | 1(True):発注, 0(False):待機 |
| 3 | 注文データ範囲 | ● | range | 複数注文のデータ範囲 |

## 使用例

### 複数銘柄の同時新規注文
```excel
=RssFOPMultiOpenOrder(1,1,A1:H5)
```

## バージョン情報
- RSS Version: 2.0
- 対応: Excel 2016以降
- 最終更新: 2024年