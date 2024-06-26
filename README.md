# item_modifier-copy_nbt
item_modifierのcopy_nbtに関するサンプルになります。

~詳しくはブログ記事『[]()』を参考にしてください。~<br>
現在執筆中

<h3>使い方</h3>

データパック導入後、ワールドに入るとアイテムを付与するコマンド、ストレージを操作するコマンドが自動的に起動します。<br>
付与されたアイテムを使用することで、スムーズにcopy_nbtを体験することが可能です。

通常とは異なるドロップ品が手に入るようデータパックを組んでいるため、「サケ、タラを倒す」、「かまどを壊す」を行ってください。

それぞれ以下のものをドロップします。

|倒す、破壊するもの|ドロップ品|
|------|------|
|サケ|ダイヤモンド|
|かまど|溶鉱炉|
|タラ|トリップワイヤーフック|

ドロップしたアイテムをdataコマンドで調べると、CustomModelDataが設定されていることが分かります。<br>
※リソースパックは作成していないため、テクスチャは変わりません

dataコマンドの一例として以下のものを置いておきます。<br>
```copy
/data get entity @s SelectedItem
```

メインハンドに持っているアイテムを調べるので、手に持った状態で実行すること。
