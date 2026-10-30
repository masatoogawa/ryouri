# うちのレシピ

GitHub Pages で公開している家庭用レシピ集。ビルドなしの素の HTML。

## レシピを追加するとき
1. `recipes/<英数字ファイル名>.html` に作成する（URL を見やすくするため日本語ファイル名は使わない）
2. デザインは `recipes/takikomi-gohan.html` を雛形にする（配色・書体・カード構成をそろえる）
3. ページ先頭に `<a class="back" href="../index.html">← レシピ一覧</a>` を入れる
4. `index.html` の該当カテゴリ（なければ `<section>` を追加）にリンクを足す
