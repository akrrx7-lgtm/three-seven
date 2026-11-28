THREE SEVEN v1.11 接続情報設定済み版

1. Firebase コンソールの Realtime Database → ルール を開く。
2. three_seven_rules_paste.txt の内容を全てコピーし、既存のルールを置き換えて「公開」。専用データベースの場合のみ。テストモードにしない。
3. index.html を GitHub Pages の既存の index.html と差し替える。接続設定は HTML に内蔵済みなので別ファイルは不要。
4. 必要に応じ Authentication → 設定 → 承認済みドメインに GitHub Pages のホスト名を追加する。
5. 公開URLを2端末で開き、オンライン対戦で部屋作成・参加・攻撃・再戦を試す。

匿名認証を有効にした状態で使用。Google Analytics は組み込んでいない。
実Firebase通信およびルールの実環境検証は未実施。
Spark無料プランを維持し、使用量を確認する。
