# Information
Githubを使う上での規約・説明など
//TODO: 内容が増えてきたら最重要以外はWikiに移行

# README.mdやwikiの編集について

+ Markdownで行います(記法が特殊), GUIエディタ使わない感じです
+ [Markdownチートシート](http://qiita.com/Qiita/items/c686397e4a0f4f11683d)
+ Githubから編集すればGUIでもいけるかも


# Gitの追跡対象とするファイルについて

+ 基本Assetsはリポジトリに放り込んでCommitとかすればいいです
+ 重い(40~100M超える)ファイルについては外部サーバに挙げるとかしてください
+ metafileとかは口述の.gitignoreを使って追跡対象としない(プロジェクト壊れちゃ＾～う)
+ なぜプロジェクトが壊れるかはこのページがわかりやすいです. [Unityのプロジェクトはなぜ壊れるのか](http://madnesslabo.net/utage/?page_id=5640)

# Gitignore

Gitでバージョン管理しないファイル指定するためのファイルです。
作ったリポジトリに応じて放り込んでください.

### 注意事項

+ ファイル名は.gitignoreにする
+ 原則として使用する.gitignoreファイルは1つまで, 複数ある場合は深い階層のものが優先される


### 使用する.gitignore 

+ Unityの場合: Unity.gitignore


#ユーザ権限

基本memberで, 操作なれてきたらownerにするとか?