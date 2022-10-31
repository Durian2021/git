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



a

|                main                |                                       説明                                        |                          コマンド                           |
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

