# bbsite_term_icon モジュール

コンテンツタイプに追加した Term reference フィールドの表示方法として **アイコンリンク**
を追加するモジュールです。

例えば、[BBSite の技術 BLOG](http://bbsite.jp/blog) のように動作します。

Term に追加した Image フィールドを使って、Node のカテゴリアイコンとして表示します。

このモジュールは Drupal 7.x で動作します

## Install

モジュールをダウンロードし、モジュールフォルダ (sites/all/modules 等)に展開します。
モジュールを *有効* にします。

Taxonomy 管理ページで、アイコンを追加したい Vocabulary を選び、 *edit vocabulary*
をクリックします。

**MANAGE FIELDS** タブで、フィールドタイプが *Image* のフィールドを追加します。

次に、この Vocabulary を利用しているコンテンツタイプ(例: Article) の表示フィールド
管理画面に移動します(admin/structure/types/manage/<content type>/display)。

先程設定した Vocabulary の関連付けられた Term reference フィールドの表示フォーマッ
トプルダウンをクリックし、 **Icon liink** を選択します。

表示オプションの設定で、**Image style** と **Image Field** を選択し、保存します。

これで、term に設定された Image フィールドの画像がアイコンとして表示されるようにな
ります。


