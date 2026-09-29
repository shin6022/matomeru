# matomeru

iOSアプリ「めくりえ」のサポートページとプライバシーポリシー（GitHub Pages）。

| ページ | URL |
|---|---|
| トップ | https://shin6022.github.io/matomeru/ |
| サポート | https://shin6022.github.io/matomeru/support.html |
| プライバシーポリシー | https://shin6022.github.io/matomeru/privacy.html |

アプリの設定画面は `support.html` と `privacy.html` に直接リンクしている。ファイル名を変えるとアプリの修正が要る。

## 埋める項目

`_config.yml` の次の値を埋めると、全ページに反映される。

- `contact_email` … アプリ専用のメールアドレス
- `operator_name` … 運営者名（本名でなくてもよい。屋号やハンドル名）
- `policy_established` / `policy_revised` … 制定日・最終改定日
- `app_store_url` … App Store 公開後に入れると、トップにボタンが出る

プライバシーポリシーの本文を変えたときは、`policy_revised` を更新する（ポリシー第11条）。

## 手元で確認する

```sh
gem install jekyll kramdown-parser-gfm
jekyll serve --baseurl /matomeru
# → http://127.0.0.1:4000/matomeru/
```
