Movable Type Plugin  CEB Separating Words

内容:
    選択テキスト内でを単語らしき文字列を分かち書きに変換します。


用件 :
    Movable Type 4.x ~ 5.x + Custom と Editor Button 2 Plugin　https://github.com/aklaswad/mt-plugin-custom-editor-button-2
    * Movable Type 5.2 以降では、TinyMCE プラグインを無効

インストール:
    plugins フォルダ下の CEBSeparatingWords を Movable Typeの plugins 以下にいれます。
    /mt-static/plugins/CEBSeparatingWords は MTシステムを入れたディレクトリ/mt-static/plugins/　以下にいれます。

使用と詳細:
    記事編集画面にて、Custom Editor Button のポケット内に、_ABC_　のアイコンが追加されていますので、必要に応じて編集ボタンボックス内に移動します。
    選択したテキスト内で、単語に該当する箇所に対して、 半角スペースword半角スペース に変換します。
	連続数字には変換しないようにしています。
    仕組み上、 undo できませんので、分かち書き変換したくないテキストは選択しないようにします。
    変換のルールを変えたいときは、config.yaml の var reg = '//' の値を変えてください。

ライセンス: MIT License

2013 http://labs.markdiary.com  by maRk