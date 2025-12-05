# 段落1  
  
## 段落2  
  
### 段落3  
  
#### 段落4  
  
- 箇条書き  
  - 箇条書き  
  
1. 英数字箇条書き  
  a. 英数字箇条書き  
  
見出しとアンカー  
  
- [段落1](#段落1)  
  - [段落2](#段落2)  
    - [段落3](#段落3)  
      - [段落4](#段落4)  
  
~~打消し~~  
  
**太字**  
  
*斜体*  
  
仕切りの水平線  
  
***  
  
表  
  
| 見出し1 | 見出し2 | 見出し3 |
|--------|--------|--------|
| セル1   | セル2   | セル3   |
| セル4   | セル5   | セル6   |
  
インラインコード  
  
`ls -la`  
  
コードブロック  
  
```JAVA
// 世界に挨拶
System.out.println("Hello, World!");
```  
  
リンク  
  
[d払い](https://www.docomo.ne.jp/service/d_payment/)  
  
画像  
  
![d払いのロゴ](https://www.docomo.ne.jp/service/d_payment/images/thumb_d_payment_01.gif)  

付箋ペタペタ

> [!NOTE]
> ノート
  
> [!TIP]
> コツ
  
> [!WARNING]
> 注意！
  
> [!IMPORTANT]
> 重要！
  
> [!ERROR]
> エラー！
  
mermaidグラフ  
  
```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
  
応用編(ガントチャート)
  
```mermaid
gantt
  title プロジェクト進行
  dateFormat  YYYY-MM-DD
  section 計画
  要件定義     :done, 2024-04-01, 5d
  設計         :active, 2024-04-06, 5d
  section 実装
  フロント開発 : 2024-04-11, 7d
  バックエンド開発 : 2024-04-11, 10d
```
  
応用編(マインドマップ)  
  
```mermaid
mindmap
Root
  業務効率化
    図解化
      フローチャート
      マインドマップ
    ドキュメント整備
```
  
応用編(シーケンス図)
  
```mermaid
sequenceDiagram
    participant User as ユーザー
    participant Web as ウェブサイト
    participant Payment as 支払いゲートウェイ
    User->>Web: 商品ページを表示
    User->>Web: 購入ボタンをクリック
    Web->>Payment: 支払い情報を送信
    Payment-->>Web: 支払い確認
    Web-->>User: 購入完了メッセージを表示
```
  
応用編(UML/クラス図)
```mermaid
classDiagram
  class 商品 {
    +String 名前
    +float 価格
    +void 表示()
  }
  class カート {
    +List~商品~ 商品リスト
    +void 追加(商品)
    +void 削除(商品)
    +float 合計金額()
  }
  商品 <|-- カート
```
  
UI(チェックボックス)  
- [x] やった  
- [ ] やってない  
  
