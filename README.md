
# LIFF API テスト
## 実行環境
- mac catalina  
- homebrew
- git 
- heroku CLI
- vscode

## 初期設定方法
1. Herokuアカウントを作成、
2. コンソールから下記コマンドを実行  
git heroku CLIインストール必要です。
```yaml
#git初期化  
git init  
#herokuにログイン  
heroku login
#現在のソースをステージングに変更
git add .
#現在のソースをコミット
git commit -m "First commit"
#herokuに現在のソースをデプロイ
git push heroku master
```

 * [LINE Developers Consoleを開く](https://developers.line.me/en/docs/liff/getting-started/) 
*  [Heroku account作成](https://www.heroku.com)

3. LINE Developers Consoleで適当なチャンネルにLIFF登録を行う。  
herokuアプリで生成されたWeb URLをLiff設定画面 WebURLに入力。  
scopreは 全て許可（メッセージ送信も行うために）

4. リッチメニューから起動させるためにLIFF URLをリッチメニューに[リンク] として登録する。


## メモ
[vConsole](https://github.com/Tencent/vConsole)を導入（開発時のスマホ デバッグに使用、コンソール画面を表示可能）

参考URL