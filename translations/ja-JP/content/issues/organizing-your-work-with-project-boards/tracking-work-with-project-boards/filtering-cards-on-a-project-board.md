---
title: 'Filtering cards on a {% data variables.product.prodname_project_v1 %}'
intro: 'You can filter the cards on a {% data variables.projects.projects_v1_board %} to search for specific cards or view a subset of the cards.'
redirect_from:
  - /github/managing-your-work-on-github/tracking-the-progress-of-your-work-with-project-boards/filtering-cards-on-a-project-board
  - /articles/filtering-cards-on-a-project-board
  - /github/managing-your-work-on-github/filtering-cards-on-a-project-board
versions:
  feature: projects-v1
topics:
  - Pull requests
shortTitle: 'Filter cards on {% data variables.product.prodname_project_v1 %}'
allowTitleToDifferFromFilename: true
---

{% data reusables.projects.project_boards_old %}

On a card, you can click any assignee, milestone, or label to filter the {% data variables.projects.projects_v1_board %} by that qualifier. 検索をクリアするには、同じアサインされた人、マイルストーン、またはラベルを再度クリックします。

You can also use the "Filter cards" search bar at the top of each {% data variables.projects.projects_v1_board %} to search for cards. 以下の検索修飾子をさまざまに組み合わせて使用したり、検索したいテキストを入力したりすることで、カードをフィルタリングできます。

- `author:USERNAME` を使用してカードを作者でフィルタする
- `assignee:USERNAME` または `no:assignee` を使用して、カードをアサインされた人でフィルタリングする
- `label:LABEL`、`label:"MULTI-WORD LABEL NAME"`、または `no:label` を使用して、カードをラベルでフィルタリングする
- `milestone:MY-MILESTONE` を使用して、カードをマイルストーンでフィルタリングする
- `state:open`、`state:closed`、または `state:merged` を使用して、カードを状態でフィルタリングする
- `review:none`、`review:required`、`review:approved`、または `review:changes_requested` を使用して、カードをレビューステータスでフィルタリングする
- `status:pending`、`status:success`、または `status:failure` を使用して、カードをチェックステータスでフィルタリングする
- `type:issue`、`type:pr`、または `type:note` を使用して、カードをタイプでフィルタリングする
- `is:open`、`is:closed`、または `is:merged`と、`is:issue`、`is:pr`、または `is:note` とを使用して、カードをステータスとタイプでフィルタリングする
- `linked:pr`を使用したクローズしているリファレンスによってプルリクエストにリンクされているIssueのフィルタリング
- Filter cards by repository in an organization-wide {% data variables.projects.projects_v1_board %} using `repo:ORGANIZATION/REPOSITORY`

1. Navigate to the {% data variables.projects.projects_v1_board %} that contains the cards you want to filter.
2. プロジェクトのカード列の上で、[Filter cards] 検索バーをクリックして検索クエリを入力し、カードをフィルタリングします。 ![カードのフィルタリング検索バー](/assets/images/help/projects/filter-card-search-bar.png)

{% tip %}

**ヒント:** フィルタリングされたカードをドラッグアンドドロップしたり、キーボードのショートカットを使用して列間で移動させたりできます。 {% data reusables.project-management.for-more-info-project-keyboard-shortcuts %}

{% endtip %}

## 参考リンク

- [{% data variables.product.prodname_projects_v1 %}について](/articles/about-project-boards)
- "[Adding issues and pull requests to a {% data variables.product.prodname_project_v1 %}](/articles/adding-issues-and-pull-requests-to-a-project-board)"
- "[Adding notes to a {% data variables.product.prodname_project_v1 %}](/articles/adding-notes-to-a-project-board)"
