# RssFOPMultiCloseOrder 完全仕様書

## 概要
**関数名**: RssFOPMultiCloseOrder  
**カテゴリ**: 先物OP注文管理 (Futures & Options Order Management)  
**用途**: 先物OP複数転売買戻注文  

**説明**: 先物・オプション取引で複数建玉の決済注文を一括で行います。効率的な決済執行により、複数ポジションの同時決済が可能です。

## 構文 (Syntax)

### Excel ワークシート関数
```excel
RssFOPMultiCloseOrder(発注ID, 発注トリガー, 決済データ範囲)
```

### VBA関数
```vb
RssFOPMultiCloseOrder_V(発注ID, 決済データ範囲)
```

## パラメータ詳細

| No | パラメータ名 | 必要性 | データ型 | 説明 |
|----|------------|--------|----------|------|
| 1 | 発注ID | ● | number | 複数決済注文を識別するID |
| 2 | 発注トリガー | ● | number | 1(True):発注, 0(False):待機 |
| 3 | 決済データ範囲 | ● | range | 複数決済のデータ範囲 |

## 使用例

### 複数建玉の同時決済注文
```excel
=RssFOPMultiCloseOrder(1,1,A1:G5)
```

## バージョン情報
- RSS Version: 2.0
- 対応: Excel 2016以降
- 最終更新: 2024年