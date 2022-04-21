# subject-220422

## [簡易詳細設計書(A4)作成 : VBScript + Excel.Application](https://winofsql.jp/download/create-spec-format.zip)

<pre>
Microsoft Excel がインストールされている必要があります

ソース時用には、拡張子 .xlsx で記述していますが、.xls でも動作します。

実行すると、ドキュメントフォルダに作成されます

作成されるのは、非常にシンプルな4種類の設計書フォーマットです。
</pre>
<table id="spec"><tbody><tr>
<td><img src="https://winofsql.jp/image/a/excel-spec-1.png">
<pre>1) 概要書
　処理を中心とした入出力をオートシェイプの
　フローチャートで示し、概要を記述して正確
　な入出力エントリ列挙します
</pre>
</td> 
<td>
<img src="https://winofsql.jp/image/a/excel-spec-2.png">
<pre>2) 画面設計書
　最近では画面の画像をはりつける事がほとん
　どです
 
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
