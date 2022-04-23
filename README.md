# subject-220422

## PHP : [ヒアドキュメント構文](https://www.php.net/manual/ja/language.types.string.php#language.types.string.syntax.heredoc)paiza
### [paiza.io で実行](https://paiza.io/projects/vn-eEHX93n_QMC8735ODMA)
```php
<?php

$default_value = "こんにちは";

$view = <<<AAA
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/5.1.3/css/bootstrap.min.css">
    <div class="alert alert-primary">ヒアドキュメント</div>
    <input value="{$default_value}">
AAA;

print $view;

?>
```


## [簡易詳細設計書(A4)作成 : VBScript + Excel.Application](https://winofsql.jp/download/create-spec-format.zip)

<pre>
Microsoft Excel がインストールされている必要があります

ソース時用には、拡張子 .xlsx で記述していますが、.xls でも動作します。

実行すると、ドキュメントフォルダに作成されます

作成されるのは、非常にシンプルな4種類の設計書フォーマットです。
</pre>
<table id="spec"><tbody><tr>
<td>
<img src="https://winofsql.jp/image/a/excel-spec-1.png">
<pre>1) 概要書
　処理を中心とした入出力をオートシェイプの
　フローチャートで示し、概要を記述して正確
　な入出力エントリ列挙します
</pre>
</td> 
<td>
<img src="https://winofsql.jp/image/a/excel-spec-2.png">
<pre>2) 画面設計書
　最近では
  画面の画像を
  はりつける事がほとんどです
</pre>
</td>
</tr>
<tr>
<td>
<img src="https://winofsql.jp/image/a/excel-spec-3.png">
<pre>3) 入力設計書
　入力チェックを中心とした GUI の操作手順を
　ベースとしてアプリケーションの定義をして
　いきます。入力フィールドの属性も通常示さ
　れます
</pre>
</td> 
<td>
<img src="https://winofsql.jp/image/a/excel-spec-4.png">
<pre>4) 出力設計書
　更新処理はここで記述されます。最近では、
　DBテーブルの更新仕様と考えて良いでしょう。
　但し例外として、印刷処理のフォーマット指示
　である事もあります
</pre>

</td>
</tr></tbody></table>
