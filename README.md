# 就活トラッカー 案内サイト

Google Drive連携のプライバシーポリシー、アプリ紹介、利用条件、サポートを公開するGitHub Pagesサイトです。

- ホーム： https://job-tracker.antoru.me/
- プライバシー： https://job-tracker.antoru.me/privacy.html
- 利用条件： https://job-tracker.antoru.me/terms.html
- サポート： https://job-tracker.antoru.me/support.html

`public/` をGitHub Actionsで配信します。ビルド・npm・外部フォント・JavaScript・アクセス解析は不要です。お問い合わせ先は `contact@antoru.me` です。変更する場合はprivacy.htmlとsupport.htmlを更新してください。アプリの取り扱いを変更するときはポリシーと更新日も合わせて見直してください。

ローカル確認： `python3 -m http.server 4178 --directory public`。GitHubのSettings → PagesのSourceにはGitHub Actionsを選択します。mainへのpushで公開します。

Google Auth Platformのホームページ・プライバシーポリシー・利用規約欄に対応URLを設定します。Google側の公開・ブランド確認やドメイン所有権の要件は別途確認が必要で、このサイトの公開だけで審査完了にはなりません。Google Cloudの認証JSONやトークンをこのリポジトリへ入れないでください。

サイトの独自コード・文章はMITライセンスです。アイコンは就活トラッカーから引き継いだ生成画像です。

独自ドメインはGitHub PagesのCustom domainに `job-tracker.antoru.me` を設定し、CloudflareのCNAME `job-tracker` を `z3nchamaaa.github.io` へ向けます（DNSのみ）。Actionsで配信しているため、CNAMEファイルではなくGitHubのPages設定でドメインを管理します。
