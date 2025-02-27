---
title: Issueについて
intro: '{% data variables.product.prodname_github_issues %}を使って、{% data variables.product.company_short %}での作業に関するアイデア、フィードバック、タスク、バグを追跡してください。'
redirect_from:
  - /github/managing-your-work-on-github/managing-your-work-with-issues-and-pull-requests/about-issues
  - /articles/creating-issues
  - /articles/about-issues
  - /github/managing-your-work-on-github/about-issues
  - /issues/tracking-your-work-with-issues/creating-issues/about-issues
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
topics:
  - Pull requests
  - Issues
  - Project management
---

## GitHubとの統合

Issueを使って、開発が行われる{% data variables.product.company_short %}上での作業を追跡できます。 他のIssueもしくはPull Request内のIssueにメンションすると、そのIssueのタイムラインにはクロスリファレンスが反映され、関連する作業を追跡できるようになります。 作業が進行中であることを示すために、Pull RequestにIssueをリンクできます。 Pull Requestがマージされると、リンクされたIssueは自動的にクローズされます。

キーワードに関する詳しい情報については「[Pull RequestのIssueへのリンク](/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue#linking-a-pull-request-to-an-issue-using-a-keyword)」を参照してください。

## 素早いIssueの作成

Issueは様々な方法で作成できるので、ワークフローで最も便利な方法を選択できます。 Issueの作成は、たとえばリポジトリから、{% ifversion fpt or ghec %}タスクリストのアイテムから、{% endif %}プロジェクトのノート、IssueあるいはPull Requestのコメント、コードの特定の行、URLクエリから作成できます。 Issueは、Web UI、{% data variables.product.prodname_desktop %}、{% data variables.product.prodname_cli %}、GraphQL及びREST API、{% data variables.product.prodname_mobile %}といった好きなプラットフォームから作成することもできます。 詳しい情報については、「[Issue を作成する](/issues/tracking-your-work-with-issues/creating-issues/creating-an-issue)」を参照してください。

## 作業の追跡

プロジェクトで、Issueを整理して優先順位付けできます。 {% ifversion fpt or ghec %}大きなIssueの一部であるIssueを追跡するには、タスクリストが使えます。{% endif %}関連するIssueを分類するには、ラベルとマイルストーンが使えます。

プロジェクトに関する詳しい情報については{% ifversion fpt or ghec %}「[プロジェクト（ベータ）について](/issues/trying-out-the-new-projects-experience/about-projects)」及び{% endif %}「[プロジェクトボードでの作業の整理](/issues/organizing-your-work-with-project-boards)」を参照してください。 {% ifversion fpt or ghec %}タスクリストに関する詳しい情報については「[タスクリストについて](/issues/tracking-your-work-with-issues/creating-issues/about-task-lists)」を参照してください。 {% endif %}ラベルとマイルストーンに関する詳しい情報については「[作業を追跡するためのラベルとマイルストーンの利用](/issues/using-labels-and-milestones-to-track-work)」を参照してください。

## 最新情報の確認

Issueの最新のコメントの情報を得ておきたい場合には、Issueをサブスクライブして最新のコメントに関する通知を受け取ることができます。 サブスクライブした Issue の最新の更新へのリンクを素早く見つけるには、ダッシュボードにアクセスしてください。 For more information, see "[About notifications](/github/managing-subscriptions-and-notifications-on-github/about-notifications)" and "[About your personal dashboard](/articles/about-your-personal-dashboard)."

## コミュニティの管理

必要な情報を提供する、意味のあるIssueをコントリビューターがオープンするのを支援するために、{% ifversion fpt or ghec %}Issueフォームと{% endif %}Issueテンプレートが利用できます。 詳しい情報については「[有益なIssueとPull Requestを促進するためのテンプレートの利用](/communities/using-templates-to-encourage-useful-issues-and-pull-requests)」を参照してください。

{% ifversion fpt or ghec %}コミュニティを健全に保つために、{% data variables.product.prodname_dotcom %}の[コミュニティガイドライン](/free-pro-team@latest/github/site-policy/github-community-guidelines)に違反するコメントを報告できます。 詳細は「[乱用やスパムをレポートする](/communities/maintaining-your-safety-on-github/reporting-abuse-or-spam)」を参照してください。{% endif %}

## 効率的なコミュニケーション

コメントに注意してもらうために、Issue内でリポジトリにアクセスできるコラボレータを@メンションできます。 同じリポジトリ内の関連するIssueをリンクするために、`#`につづいてIssueのタイトルの一部を続け、リンクしたいIssueをクリックできます。 責任を伝えるために、Issueを割り当てることができます。 同じコメントを頻繁に入力しているなら、返信テンプレートを利用できます。
{% ifversion fpt or ghec %}詳しい情報については「[基本的な記述とフォーマットの構文](/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)」及び「[他のGitHubユーザへのIssueやPull Requestの割り当て](/issues/tracking-your-work-with-issues/assigning-issues-and-pull-requests-to-other-github-users)」を参照してください。

## Issueとディスカッションの比較

会話の中には、{% data variables.product.prodname_discussions %}に適しているものもあります。 {% data reusables.discussions.you-can-use-discussions %} Issueあるいはディスカッションを使う場合のガイダンスについては「[GitHubでのコミュニケーション](/github/getting-started-with-github/quickstart/communicating-on-github)」を参照してください。

Issue内での会話にディスカッションの方が適している場合は、Issueをディスカッションに変換できます。
{% endif %}
