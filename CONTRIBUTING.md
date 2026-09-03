# Contributing

## 基本方針

- Issue、commit、Pull Requestのタイトルと本文は、プロジェクト固有の指示がない限り日本語を使用します。
- 1 Issueを1つの独立して検証可能な成果へ分け、1 Pull Requestは原則として1 Issueだけを扱います。
- 実装前に、既存Issue、Pull Request、現在のドキュメント、Decision Recordとの重複と整合を確認します。
- `main`へ直接変更せず、branchとPull Requestを使用します。

## ドキュメント

変更IssueとPull Requestでは、次のいずれかを明示します。

- `DOC_UPDATE_REQUIRED`: 要求、仕様、設計、セキュリティ、運用、操作方法などの文書更新が必要
- `NO_DOC_CHANGE`: 現行文書の契約内に収まり、文書更新が不要。理由を必ず記載する

長期間残す必要がある方針変更にはDecision Recordを追加し、関連Issue、Pull Request、影響する文書を相互にリンクします。

## 安全性

secret、token、password、接続文字列、private URL、個人情報、顧客情報、raw provider response、raw logをIssue、Pull Request、commit、文書へ含めないでください。
