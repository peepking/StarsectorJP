# StarsectorJP - Starsector 日本語化MOD

## 概要

Starsectorの日本語化MOD（日本語化パッチ）です。  
Starsector本体のcsvおよびjsonファイルで対応できる範囲を日本語化しています。

翻訳は機械翻訳をベースとしており、現在は精査を行っていないため、今後翻訳を修正する場合があります。

## 注意

別途日本語フォントが必要になります。  
有志が作成してくれたフォントを利用してください。  
[starsector-mod-JapaneseFonts](https://github.com/hirmiura/starsector-mod-JapaneseFonts)  
ゲームバージョンが違うと怒られるので、gameVersionの部分を現在のバージョンに書き換えて下さい。  

```json
{
    "id": "JapaneseFonts",
    "name": "zja Japanese Fonts",
    "author": "hirmiura",
    "utility": "true",
    "version": "0.3.1",
    "description": "Japanese Fonts by BIZUDPGothic.",
    "gameVersion": "0.96"
}
```

## 導入方法


StarsectorJPフォルダを`Starsector\mods`に置くだけです。

## 機械翻訳の方針

本体アップデートでcsvやjsonのkey名が変更される可能性がある。  
そのため原文の英語をkey、日本語訳をvalueとして辞書形式で保存している。

