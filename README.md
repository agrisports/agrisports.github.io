# 日本アグリスポーツ協会 LP

日本アグリスポーツ協会の公式ランディングページです。農業、スポーツ、教育、地域共創を軸に、体験希望者、導入検討者、認定パートナー候補へつながる静的サイトとして作成しています。

## ファイル構成

```text
.
├── index.html
├── style.css
├── script.js
├── README.md
└── assets/
    └── images/
        ├── hero-field.svg
        ├── sport-mowing.svg
        ├── sport-potato.svg
        ├── sport-corn.svg
        ├── case-family.svg
        ├── case-school.svg
        ├── case-camp.svg
        └── project-field.svg
```

## 画像差し替え方法

`assets/images/` にあるSVGは仮画像です。実際の写真に差し替える場合は、同じファイル名で上書きするか、`index.html` の `img src="assets/images/..."` を新しい画像ファイル名に変更してください。

推奨画像サイズは以下です。

- ファーストビュー：横1200px以上
- 競技カード：横800px以上
- 事例カード：横800px以上
- 地域共創画像：横1000px以上

## 問い合わせ先URLの差し替え方法

現在の問い合わせ先は仮で `info@example.com` です。`index.html` 内の `mailto:info@example.com` と表示テキスト `info@example.com` を正式なメールアドレスに差し替えてください。

Googleフォームや予約フォームを使う場合は、CONTACTセクションの以下のリンクを実際のURLに変更してください。

- `資料をダウンロードする`
- `オンライン相談を申し込む`

現在はどちらも仮の `mailto:` リンクです。`href="mailto:..."` を `href="https://forms.gle/..."` のように置き換えるだけで使えます。

## GitHub Pagesで公開する手順

1. このフォルダの内容をGitHubリポジトリにアップロードします。
2. GitHubのリポジトリ画面で `Settings` を開きます。
3. `Pages` を開き、`Build and deployment` の `Source` を `Deploy from a branch` にします。
4. 公開するブランチを選び、フォルダは `/root` を選択します。
5. 保存後、表示されるGitHub PagesのURLにアクセスします。

HTML、CSS、JavaScriptのみで作成しているため、ビルド作業は不要です。
