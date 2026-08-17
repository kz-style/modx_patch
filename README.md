# MODX Evolution 1.2.xJ のパッチ集

## 反映方法：
修正版ファイルをMODX Evolution の該当ディレクトリへ配置（ファイル置換）してください。

## 注記：
各ファイルには修正箇所に「日付 Added(またはEdited) by K'z Style」のコメントを（極力）入れています。
修正版ファイルと共にオリジナルファイルを「xxx.org」の拡張子で保存しています。

## 変更履歴:
- 2026.08.17 MODX Evolution 1.2.1J のパッチ
    - ./assets/snippets/ditto/classes/template.class.inc.php --> Dittoエラー対応
    - ./manager/actions/element/mutate_tmplvars.dynamic.php --> $chkエラー（テンプレート変数の所属グループタブ表示時にエラーとなる）対応、Undefined variable $notPublic（テンプレート変数の所属グループタブ表示時にエラーとなる）対応
    - ./manager/actions/document/mutate_content/fields.php --> TinyMCEをコードエディタに切り替えた際に発生するエラー対応
    - ./manager/actions/document/mutate_content/functions.php --> グループ管理を有効にした時、グループ制限なし(Public) が必ず有効になってしまう件の対応
    - ./manager/actions/document/resources_list.static.php --> $topicPathエラー対応
