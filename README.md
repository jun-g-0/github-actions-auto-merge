# github-actions-auto-merge

GitHub Actions の素振りレポジトリ。main に Push すると、main の HEAD を release へマージする。

## 調査結果

[このレポジトリの Wiki へ記載する](https://github.com/jun-g-0/github-actions-auto-merge/wiki)

## 実現したい挙動

### シナリオ A

1. main へ Push されたら、main から release への Merge する

### シナリオ B

1. main へ Push されたら、main から release への PR を作成する
2. (ボーナス)PR の URL を Slack へ送信する

### シナリオ C

1. main へ Push されたら、Slack へ、「main から release へ Merge する GitHub Actions」をトリガーする URL を投稿する
