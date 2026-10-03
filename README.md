# mizuki-y0430.github.io

Mizuki-y0430 のプロジェクト案内と、COMPOTA の公開説明・方針ページです。
ビルド不要の日本語 HTML / CSS で構成しています。

## ファイル

| ファイル | 内容 |
| --- | --- |
| `index.html` | リポジトリ全体の入口 |
| `compota/index.html` | COMPOTA の紹介・各方針へのリンク |
| `compota/privacy-policy.html` | プライバシーポリシー |
| `compota/terms.html` | 利用規約 |
| `compota/support.html` | 連携解除・データ削除・お問い合わせ |
| `compota/styles.css` | 共通スタイル（スマートフォン対応） |

## GitHub Pages で公開した場合の URL

- ホームページ：<https://mizuki-y0430.github.io/compota/>
- プライバシーポリシー：<https://mizuki-y0430.github.io/compota/privacy-policy.html>
- 利用規約：<https://mizuki-y0430.github.io/compota/terms.html>
- サポート：<https://mizuki-y0430.github.io/compota/support.html>

上記は公開後の想定 URL です。ローカルにファイルを作成するだけでは公開されません。
GitHub Pages の公開元を、このリポジトリの対象ブランチのルート `/` に設定してください。
公開後、各 URL がログイン不要で表示されることを確認してから OAuth 同意画面に登録してください。
OAuth のアプリ名と本サイトの COMPOTA 表記を一致させてください。
Google が求めるドメイン所有権の確認やアプリの審査は、ページ作成とは別の手続きです。

## 内容を変更するとき

- 対象は `calendar-bot` の COMPOTA v0。更新日は 2026年10月3日。
- 開発者・本サイト管理者は GitHub アカウント `Mizuki-y0430` としています。
- お問い合わせ先は `calendar-bot` の公開 GitHub Issues です。公開運用前に Issues が利用可能であることを確認してください。メール窓口を設ける場合は `compota/support.html` を更新してください。
- 自分以外に Bot の運用を委託する場合は、実際の運用担当者・管理方法に合わせて記述を更新してください。
- 実装を確認したうえで、Calendar のスコープ、SQLite 保存、認証 JSON 保存、自動消去がないことを記載しています。未実装の暗号化・自動削除を実装済みとは記載していません。
- OAuth 認証情報と SQLite は現状アプリ側で暗号化されません。公開運用にあたっては、OS のディスク暗号化等を含む保存時の保護と Google の要件の適合を確認してください。ポリシーを掲載するだけで実装の適合が保証されるものではありません。
- 取得情報、保存方法、共有先、利用目的が変わるときは、ポリシー・削除手順・更新日を併せて更新してください。
- 認証トークン、OAuth クライアント JSON、`.env`、データベース、個人情報を含むログを、この公開リポジトリへ追加しないでください。

## 参考にした公式資料

- [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy)
- [Google Workspace API user data and developer policy](https://developers.google.com/workspace/workspace-api-user-data-developer-policy)
- [OAuth 2.0 Policies](https://developers.google.com/identity/protocols/oauth2/policies)
- [Google アカウントのサードパーティ接続管理](https://support.google.com/accounts/answer/13533235?hl=ja)
- [GitHub Pages の説明・データ収集](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages)
