# Review pull requests（日本語版）

_他の人と協力して作業を磨き、マージする前に提案をもらう。_

> このリポジトリは GitHub Skills「[Review pull requests](https://github.com/skills/review-pull-requests)」（MIT License）の日本語版です。
> 演習の進め方と自動チェックの仕組みは原本と同じで、Issue に投稿される手順の本文だけを日本語にしています。

## ようこそ

優れたプロジェクトはどれも共同作業から始まります。pull request は、GitHub でのチーム作業の土台です。コメントする、変更を依頼する、承認するといった操作を通じて、時間や場所を合わせずに一緒に作業し、成果を磨き上げられます。

- **対象**: 開発者、開発以外の共同作業者、学生、マネージャー
- **学ぶこと**:
  - レビューを依頼し、担当者を割り当てる方法
  - 他の人の作業をレビューする方法
  - 変更を提案し、変更を承認する方法
- **作るもの**: 簡単なゲームの pull request をレビューします
- **前提**: [Introduction to GitHub](https://github.com/skills/introduction-to-github) の演習の内容を理解していること
  - コミット
  - ブランチと pull request の作成
- **所要時間**: 30 分以内

この演習で行うこと:

1. pull request を開く
2. 自分を担当者にする
3. レビューする
4. 変更を提案する
5. 変更を適用する
6. pull request をマージする

### 演習の始め方

演習を自分のアカウントにコピーし、Octocat（Mona）が最初のレッスンを準備するまで **20 秒ほど**待ってから、**ページを再読み込み**してください。

[![](https://img.shields.io/badge/Copy%20Exercise-%E2%86%92-1f883d?style=for-the-badge&logo=github&labelColor=197935)](https://github.com/new?template_owner=mamezou&template_name=skills-ja-review-pull-requests&owner=%40me&name=skills-review-pull-requests&description=Exercise%3A+Review+pull+requests&visibility=public)

<details>
<summary>うまくいかないとき 🤷</summary><br/>

演習をコピーするときは、次の設定を推奨します。

- Owner は自分の個人アカウント（または演習を置く Organization）を選ぶ。
- private リポジトリは [Actions の実行時間を消費する](https://docs.github.com/en/billing/managing-billing-for-github-actions/about-billing-for-github-actions)ため、public リポジトリを推奨します。

20 秒待っても演習が始まらないときは、次を確認してください。

1. リポジトリを作成したあと 20 秒ほど待ち、ページを再読み込みします。
2. リポジトリに作成された Issue の手順に従って進めます。
3. ページが自動で更新されないときは、[Actions](../../actions) タブを確認します。
   - ジョブが実行中かどうかを見る。少し長くかかることがあります。
   - ジョブが失敗している場合は、講師に知らせてください。

</details>
