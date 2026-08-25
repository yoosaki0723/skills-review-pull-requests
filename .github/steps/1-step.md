## Step 1: pull request を開く

まずは、`update-game` ブランチに最近追加された変更について **pull request** を開くところから始めます。

### 📖 理論: pull request とは

**pull request** は、あるブランチの作業を別のブランチへマージする前にレビューするための共同作業の場です。会話の管理と変更の確認をしやすくするため、いくつかのタブに分かれています。

- **Conversation** - pull request の活動記録です。共同作業者やコミュニティが、アイデア・提案・全般的なフィードバックを書き込む場でもあります。
- **Commits** - 提案元のブランチにだけ存在するコミットの一覧です。
- **Checks** - [GitHub Actions](https://github.com/features/actions) による自動処理を pull request に適用したときの結果です。Checks は別の演習で扱います。😎
- **Files Changed** - 変更前後を見比べられる [Diff](https://docs.github.com/en/get-started/learning-about-github/github-glossary#diff) の表示です。Diff の画面からコメントやレビューを追加することもできます。

> [!TIP]
> 作業が途中のものは、[下書きの pull request（draft pull request）](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)として作成できます。誤ってマージされたり、早すぎるタイミングでレビューされたりするのを防げます。

### ⌨️ やること: pull request を作る

1. ブラウザーで新しいタブを開き、演習用のリポジトリを開きます。説明は元のタブで読み、操作は新しいタブで行います。

1. 上部のメニューで **Pull requests** タブを選びます。

1. 右側の **New pull request** ボタンをクリックします。

1. **Compare changes** の欄で次のとおり選び、**Create pull request** ボタンをクリックします。

   - **base:** `main`
   - **compare:** `update-game`

1. **title**（タイトル）と **description**（説明）に次の内容を入力します。

   ```md
   Update game over message
   ```

   ```md
   Update the game over message so people know how to play again!
   ```

1. **Create pull request** をクリックします。

1. pull request ができたので、Mona が作業を確認しています。少し待って、コメントを見てください。進捗と次の Step が投稿されます。
