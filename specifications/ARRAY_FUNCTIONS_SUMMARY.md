# RSS配列数式関数まとめ

## 配列数式として動作する関数

テストにより以下の関数が配列数式であることを確認：

### 口座・取引関連
- **RssBuyingPower** - 買付余力情報
- **RssExecutionList** - 約定履歴リスト
- **RssPositionList** - 建玉情報リスト  
- **RssOrderList** - 注文リスト

### チャート・分析
- **RssChart** - チャートデータ（OHLC）

### 市場データ詳細
- **RssMarketDes** - 銘柄詳細情報
- **RssTickList** - ティック履歴

## 配列数式の使用方法

1. **範囲選択**: 十分な範囲を選択（例：A1:F20）
2. **数式入力**: 通常通り関数を入力
3. **配列確定**: **Ctrl+Shift+Enter** で確定

## よくあるエラー

### 「ヘッダー行は、単一行のセル範囲で入力してください。」
- **原因**: 単一セルに配列数式を入力
- **対処**: 範囲選択してCtrl+Shift+Enterで実行

### 全セルに同一エラーコード表示
- **原因**: データ取得エラー、認証問題
- **対処**: 市場時間、接続状況、認証設定を確認

## 単一値関数（非配列）

比較参考として、以下は単一値を返す関数：

- **RssMarket** - 個別銘柄市況
- **RssIndexMarket** - 指数情報  
- **RssFXMarket** - 為替レート
- **RssMarketHeader** - 市況ヘッダー

## テスト結果サマリー

### 動作確認済み関数（11関数）
1. **RssMarket** ✓ 単一値
2. **RssIndexMarket** ✓ 単一値（N225のみ）
3. **RssBuyingPower** ✓ 配列数式
4. **RssChart** ✓ 配列数式
5. **RssFXMarket** ✓ 単一値（データなし）
6. **RssExecutionList** ✓ 配列数式
7. **RssPositionList** ✓ 配列数式
8. **RssOrderList** ✓ 配列数式
9. **RssMarketDes** ✓ 配列数式
10. **RssTickList** ✓ 配列数式
11. **RssMarketHeader** ✓ 単一値

### 配列数式 vs 単一値の割合
- **配列数式**: 7関数 (64%)
- **単一値**: 4関数 (36%)

---
*このサマリーは実際のテスト結果に基づいて作成されています。*

### 新たに確認された配列数式関数（バッチテスト結果）

#### Chart・分析追加
- **RssTrendSMA** - 移動平均トレンド分析

#### Margin・信用取引追加  
- **RssMarginInfo** - 信用取引情報
- **RssMarginPower** - 信用余力情報
- **RssMarginPositionList** - 信用建玉リスト

#### 先物・オプション追加
- **RssFOPMarketDes** - 先物オプション銘柄詳細

### 更新後の配列数式関数総数

**確認済み配列数式関数: 12関数**

（従来の7関数 + 新規5関数）
