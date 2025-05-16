# My Repository

このリポジトリは Google Apps Script の Add-on 用に使用するアイコン画像をホストするためのものです。

## 内容

- **icon.png**  
  Google Apps Script Add-on のアイコンとして利用できる画像ファイルです。

## 利用方法

1. このリポジトリは GitHub Pages 経由で公開されています。  
   画像ファイルは次の URL から直接参照できます:  
   `https://kosuke12-takeuchi11.github.io/my-repository/gmail_salinks.png`

2. Google Apps Script のプロジェクトで、Add-on のマニフェストファイル (`appsscript.json`) に `logoUrl` プロパティとして上記の URL を設定することで、アイコン画像として利用できます。

   ```json
   {
     "addOns": {
       "common": {
         "name": "My Add-on",
         "logoUrl": "https://kosuke12-takeuchi11.github.io/my-repository/gmail_salinks.png"
       }
     }
   }
