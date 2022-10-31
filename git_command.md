### おすすめGUI Linuxでは無理！
Sourcetree(Linux☓)
Fork(有料)
<br>
https://codelikes.com/vscode-git-plugin/
# 流れ
### working tree
↓
- git add 
    - Gitに追加してねとお願いするコマンド

### index
↓
- git commit
  - Gitに保存してねとお願いするコマンド
  
↓
### repository

↓
- push
  - Git に GitHubに送信してねとお願いするコマンド



| main                               | 説明                                                                              | コマンド                                                    |
| ---------------------------------- | --------------------------------------------------------------------------------- | ----------------------------------------------------------- |
| git init                           | 対処の                                                                            | cd ./localrepository <br> git init                          |
|                                    |                                                                                   |                                                             |
| git add .                          | 全てのディレクトリをステージング                                                  |                                                             |
| git add ファイル名                 | 対象のファイルをステージング                                                      | git add git_command.md                                      |
|                                    |                                                                                   |                                                             |
| git commit -m 'コミットメッセージ' | ローカルリポジトリにコミット <br>コミットするとcommit IDが割り振られる            | git add git_command.md<br> git commit -m 'コマンド一覧編集' |
|                                    |                                                                                   |                                                             |
| git status                         | 今の状態を確認(変更したか、ステージングされているか)                              | git status                                                  |
| git log                            | 今までのログが見れる、オプションが多い。<br>Gitクライアントアプリ使った方が良い!! |                                                             |
|                                    |                                                                                   |                                                             |

### ブランチ操作
| main                                           | 説明                         | コマンド                 |
| ---------------------------------------------- | ---------------------------- | ------------------------ |
| <font color="Red">git switch ブランチ名</font> | 指定ブランチに切り替え       |                          |
| git switch -c 新しいブランチ名                 | 指定ブランチを作成/切り替え  | git switch -c feature/01 |
|                                                |                              |                          |
| <font color="Red">git branch </font>           | ブランチの一覧を表示         | git branch               |
| git branch -d ブランチ名                       | 指定ブランチの削除           | git branch -d feature/01 |
|                                                |                              |                          |
| git merge ブランチ名                           | 分岐したブランチをマージする | git merge ブランチ名     |
|                                                |                              |                          |





### 前の状態に戻す
|                main                 |                説明                |                            コマンド                             |
| ----------------------------------- | ---------------------------------- | --------------------------------------------------------------- |
| git restore . --source 戻したい場所 | 指定位置まで戻る                   | git restore . --source 4c1794f6d6e87e5c2845fcb8060c8b0cedd676fd |
| git restore . --source HEAD~2       | 最終コミットがHEAD、その前がHEAD~1 |                                                                 |
|                                     |                                    |                                                                 |
|                                     |                                    |                                                                 |
|                                     |                                    |                                                                 |
|                                     |                                    |                                                                 |
