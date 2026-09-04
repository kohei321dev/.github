# Contributing

## 基本方針

- Issue、commit、Pull Requestのタイトルと本文は、プロジェクト固有の指示がない限り日本語を使用します。
- 1 Issueを1つの独立して検証可能な成果へ分け、1 Pull Requestは原則として1 Issueだけを扱います。
- 実装前に、既存Issue、Pull Request、現在のドキュメント、Decision Recordとの重複と整合を確認します。
- `main`へ直接変更せず、branchとPull Requestを使用します。

## 変更・改善の相談

変更提案用のIssue Formは、検討を始めるための入口です。起票時は変更区分、解決したい問題、期待する成果を必須とし、根拠、関連文書、対象範囲などは分かる範囲で記載します。

Issue作成後、実装を始める前にplanning・実装前評価を行い、少なくとも次の情報をIssue本文へ補完します。

- 対象範囲と対象外
- ドキュメント影響と更新計画または更新不要の理由
- Decision Recordの要否
- 検証可能な完了条件
- 検証方法
- 依存関係と重複候補

Issueの作成だけでは実装開始の承認になりません。人間が実装対象のIssueを選択し、実装開始を明示的に承認してからbranchとPull Requestを作成します。

## ドキュメント

変更IssueとPull Requestでは、次のいずれかを明示します。

- `DOC_UPDATE_REQUIRED`: 要求、仕様、設計、セキュリティ、運用、操作方法などの文書更新が必要
- `NO_DOC_CHANGE`: 現行文書の契約内に収まり、文書更新が不要。理由を必ず記載する

長期間残す必要がある方針変更にはDecision Recordを追加し、関連Issue、Pull Request、影響する文書を相互にリンクします。

## 安全性

secret、token、password、接続文字列、private URL、個人情報、顧客情報、raw provider response、raw logをIssue、Pull Request、commit、文書へ含めないでください。
