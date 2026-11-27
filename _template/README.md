# 新しいアプリを追加する手順

このフォルダ（_template）はサイトには公開されません（先頭が「_」のフォルダはGitHub Pagesで公開されないため）。

1. `_template/index.html` をコピーして、`<アプリの英字名>/index.html` として新しく作る（例：`mystery3/index.html`）
2. `{{アプリ正式名}}` `{{アプリ名}}` `{{キャッチコピー}}` `{{アプリ紹介文（2〜3文）}}` を書き換える
3. アイコン画像を `<アプリの英字名>/icon.png` に置く（なくても表示は崩れない）
4. トップの `index.html` の「アプリ一覧」にカードを1つ追加する
5. App Store Connect に入れるURL
   - サポートURL：`https://y3595780-boop.github.io/<アプリの英字名>/`
   - プライバシーポリシーURL：`https://y3595780-boop.github.io/privacy.html`（全アプリ共通）
   - マーケティングURL（任意）：`https://y3595780-boop.github.io/`
6. app-ads.txt は全アプリ共通。新しい広告ネットワークを追加したときだけ行を足す

広告のしくみ（AppLovin MAX）や取得する情報を変えたときは、`privacy.html` も直す。
