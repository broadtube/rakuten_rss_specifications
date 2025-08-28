# RssFOPCapacityList 完全仕様書

## 概要
**関数名**: RssFOPCapacityList  
**カテゴリ**: 先物OP資産情報 (Futures & Options Asset Information)  
**用途**: 余力情報（先物OP）の取得  

**説明**: 先物・オプション取引における証拠金余力や必要証拠金等の情報をExcelに表示します。先物・オプション取引のリスク管理と資金管理に活用できます。

## 構文 (Syntax)

### Excel ワークシート関数
```excel
RssFOPCapacityList(引数列, ヘッダ行)
```

### VBA関数
```vb
RssFOPCapacityList_V(引数列, ヘッダ行)
```

## パラメータ詳細

| No | パラメータ名 | 必要性 | データ型 | 説明 |
|----|------------|--------|----------|------|
| 1 | 引数列 | ● | number | データ列の開始位置を指定する数値 |
| 2 | ヘッダ行 | ● | number | ヘッダ行の位置を指定する数値 |

## 使用例

### 基本的な先物OP余力情報取得
```excel
=RssFOPCapacityList(A1, 1)
```

## 戻り値

### 実際の出力例
| 項目 | 金額 |
|------|------|
| 証拠金余力 | 500000 |
| 必要証拠金 | 1540000 |
| 追加証拠金 | 0 |
| 証拠金維持率 | 132.5 |
| 委託証拠金 | 2000000 |

## 関連関数
- **RssFOPPositionList**: 先物OP建玉一覧
- **RssFOPOrderList**: 先物OP注文一覧
- **RssCapacityList**: 余力・保証金額

## バージョン情報
- RSS Version: 2.0
- 対応: Excel 2016以降
- 最終更新: 2024年