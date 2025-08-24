## SOLID原則
### S - 単一責任の原則（SRP）
- クラスは「1つの責任」のみを持つべき
### O - オープン/クローズドの原則（OCP）
- 拡張に対して開かれ、修正に対して閉じているべき
### L - リスコフの置換原則（LSP）
- サブクラスは親クラスと置き換えても正しく動作すべき
### I - インターフェース分離の原則（ISP）
- クライアントに不要なメソッドを強制しない
### D - 依存性逆転の原則（DIP）
- 実装よりも抽象に依存すべき

## デザインパターン
- https://refactoring.guru/ja/design-patterns/catalog
- https://tamotech.blog/2024/03/12/gof-design-pattern/
### シングルトン
```java
public class Card {

    private static final Card card = new Card();

    // コンストラクタ
    private Card() {
        // Cardクラスのインスタンスの初期化処理
    }

    public static Card getInstance() {
        return card;
    }
}
```



